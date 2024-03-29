Created: March-22-2024

Thread cancellation is the task of terminating a thread before it is completed.

Examples -

- If multiple threads are concurrently searching through a database and one thread returns the result, the remaining threads might be cancelled
- When a user presses stop button on a [[Web Browser]] all threads loading the page are cancelled

So it's quite clear that Thread Cancellation is a very common activity.

A thread to be cancelled is referred to as the **target thread**
## Cancellation Scenarios

1. Asynchronous cancellation - One thread immediately terminates the target thread
2. Deferred cancellation - Target thread periodically checks whether it should terminate, allowing an opportunity for itself to terminate gracefully
## Problems

1. When resources have been allocated to a cancelled thread
2. When a thread is cancelled in the midst of updating data

The OS reclaims system resources from a cancelled thread but it may not be able to reclaim all resources. Hence, cancelling a [[Thread]] asynchronously is bad!

With **deferred cancellation** one thread indicates that a target thread needs to be cancelled.

But cancellation occurs only after strict validation, in case of failure the thread indicating the **target thread** also has the authority to cancel the cancellation!
# Related Notes

1. [[Operating System]]
# References

1. 