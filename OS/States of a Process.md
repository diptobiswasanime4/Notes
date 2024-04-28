Created: April-28-2024

A process can have the below state.
## New State

Process is about to be created. Program is still in [[Secondary Memory]]

Technically process is not yet created, but we call that the process is in New State.
## Ready State

The process is created and it is residing in [[Main Memory]] and it is ready to be executed

So from Hard Disk a Program is taken by the [[Scheduler]] and brought into the Primary Memory and converted into a Process, which is in Ready State

There can be many Processes in New or Ready State
## Running State

If a process is executing in [[CPU]] then it is in Running State.

If we have 1 CPU, only 1 Process can run at a time
## Block or Wait

A process may need I/O or gets blocked because of some events, then it will go to Block or Wait state

This is similar to pre-emption of a process.
## Termination or Completion

Once the process finishes it is killed

Context or PCB is deleted

![[Process state flow excal.excalidraw]]
## Suspend Ready

If there is no space in the [[Main Memory]] then one of the processes must be moved to the [[Secondary Memory]] to create more space

The process in this case will move to Suspended Ready from being Ready

It will become ready once again when memory is available
## Suspend Wait or Suspend Block

When Main Memory is not available we can push a process in the Wait or Block state to the Secondary Memory. Then it becomes Suspend Wait or Suspend Block

This is better than Suspend Ready

![[Wait Block process flow.excalidraw]]

# Related Notes

1. [[Operating System]]
# References

1. 