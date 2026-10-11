# Processes And Signals

Exercises for this part of the course. The file table below describes the saved scripts and answers.

| File | What it does |
| --- | --- |
| [0-what-is-my-pid](0-what-is-my-pid) | Prints the current script's process ID. |
| [1-list_your_processes](1-list_your_processes) | Shows processes in a tree-style ps listing. |
| [10-process_and_pid_file](10-process_and_pid_file) | Writes a PID file, handles signals, and removes the PID file on selected exit paths. |
| [11-manage_my_process,](11-manage_my_process,) | Starts, stops, or restarts manage_my_process using a PID file; the filename ends in a comma. |
| [2-show_your_bash_pid](2-show_your_bash_pid) | Finds lines containing bash in the process list. |
| [3-show_your_bash_pid_made_easy](3-show_your_bash_pid_made_easy) | Reads /proc to print process IDs whose command names contain bash. |
| [4-to_infinity_and_beyond](4-to_infinity_and_beyond) | Prints a message every two seconds until stopped. |
| [5-dont_stop_me_now](5-dont_stop_me_now) | Finds and signals running copies of 4-to_infinity_and_beyond. |
| [6-stop_me_if_you_can](6-stop_me_if_you_can) | Finds the loop process and attempts to write to its /proc entries. |
| [7-highlander](7-highlander) | Runs a loop and handles SIGTERM by printing a message. |
| [8-beheaded_process](8-beheaded_process) | Finds and sends the default kill signal to 7-highlander processes. |
| [manage_my_process](manage_my_process) | Appends I am alive! to /tmp/my_process every two seconds. |
