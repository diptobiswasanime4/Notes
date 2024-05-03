Created: May-03-2024

Spin Lock is also called Priority inversion

Let's assume P1 has lesser Priority than P2

P2 arrives in the Entry of the [[Critical Section]] and is stuck in the entry loop

P1 is in the Critical Section hence can not be preempted

And both the processes gets stuck

This situation is called Priority inversion or Spin Lock

In this case P1 wants [[CPU]], has [[Critical Section]] and P2 wants [[Critical Section]], has [[CPU]]
## Lock Variable

Mechanism implemented in User mode

Lock = 0 means [[Critical Section]] is available

Lock = 1 means [[Critical Section]] is unavailable

Lock is like a flag

	loop
	lock = 1 // entry
	Critical Section
	lock = 0 // exit

*When [[Busy Waiting]] is mixed with Priorities there will be issues of **Priority Inversion***

Assembly Code:

	Load Lock, R0
	Cmp R0, 0
	JNZ Step 1 // Jump if not Zero
	Store 1, Lock
	Critical_Section
	Store 0, Lock

Since Lock value is also a common resource, now we need synchronization for Lock

Critical Section has Common Resources. So we need Synchronization. So we brought Lock variable. Lock variable is also Common resource. Hence we need Synchronization for Lock variable.

	Load Lock, R0 // gap in
	Cmp R0, 0 // loading value
	JNZ Step 1 // and locking it
	Store 1, Lock // So reduce the gap
	Critical_Section
	Store 0, Lock

What we need is something like this,

	Load Lock, R0
	Store 1, Lock
	Cmp R0, 0
	JNZ Step 1 // Jump if not Zero
	Critical_Section
	Store 0, Lock

Still there is a problem if preemption happens between 1 and 2

So we need to make step 1 and 2 as atomic. The OS will help us do it using Test Set Lock (TSL)

```cpp
{
	int TSL (int lock) {
		int R0 = lock;
		lock = 1;
		return R0;
	}
// Code
	do {
		while (TSL(lock)) {
			// Critical Section
			lock = 0;
		}
	} while (1)
}
```

The above Code smartly makes line 1 and 2 atomic using a function TSL

Now let's analyze if 4 conditions of [[Synchronization Mechanism]] is followed

1. Mutual Exclusion - only 1 process enters CS
2. Progress - Uninterested process won't enter CS
3. Bounded waiting - No unfortunately, it may cause issues for [[Busy Waiting]]
4. Architectural Neutrality - It requires support from OS, so no
# Related Notes

1. [[Operating System]]
# References

1. 