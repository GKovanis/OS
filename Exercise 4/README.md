# Exercise 4 (Scheduling)

In the **first exercise** we are requested to create a _round-robin scheduler_ in user space. Each process has a time quantum that it can run on before stopped. SIGSTOP and SIGCONT are used to interrupt and activate every process.

In the **second exercise** we are requested to expand the code in the first exercise and check the scheduler using Shell. Shell accepts commands for users, creates the appropriate request and sends them to the scheduler.

In the **third exercise** we are requested to expand the code in the second exercise and have a HIGH,LOW priority to all processes. Every process will be characterized as either HIGH or LOW. If there are any HIGH processes, they are always executed first before LOW.
