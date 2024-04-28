Created: April-28-2024

There are 3 kinds of Schedulers:

1. Long-term Scheduler - Creating a process is done by LTS
2. Short-term Scheduler - Scheduling a process from Ready to run is done by STS
3. Med-term Scheduler - Suspending a process is done by MTS

In the $Ready \longrightarrow Run$ state choosing a process is done by the Short-term Scheduler

But [[Context Switching]] is done by another software called **Dispatcher**

The dispatcher removes older process from [[CPU]] if there is, and inserts the newer process

![[ready to run scheduler excal.excalidraw]]

# Related Notes

1. [[Operating System]]
# References

1. 