1. List all of the main states a process may be in at any point in time on a standard Unix system. Briefly explain what each of these states mean.

    - Created - When a process is first created and waiting to be moved to the ready state.
    - Ready - When a process has been loaded into the cpu memory and is waiting to be executed.
    - Running - When a process is being run by the cpu.
    - Blocked - When a process is sopped from execution due to needing an external change in state or event.
    - Terminated - When a process is done executing or it can be terminated by being killed.

2. What is a Zombie Process? How does it get created? How does it get destroyed?
    - Happens after 

3. Describe the job of the Scheduler in the OS in general.
    - The job of the scheduler is to allocate resources to tasks and dertermine the amount of time that should be allocated for each task.

4. Describe the benefits of the MLFQ over a plain Round-Robin scheduler
    -   Round-Robin doesn't prioritize for different processeses it will give each process a turn before coming back to the process that may need to have it's turn before others. MLFQ changes priority of processeses and makes decisions based on the behavior of the processeses.