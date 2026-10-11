# File guide

A short description of each project file. The numbered coursework files are separate exercises.

## Root files

| File | What it does |
| --- | --- |
| [FILES.md](FILES.md) | A short guide to the files in this repository. |
| [README.md](README.md) | Project overview and instructions for readers. |

## init_files_variables_and_expansions

| File | What it does |
| --- | --- |
| [0-alias](init_files_variables_and_expansions/0-alias) | Defines ls as an alias for rm -f *. |
| [1-hello_you](init_files_variables_and_expansions/1-hello_you) | Prints a greeting using the current USER value. |
| [10-love_exponent_breath](init_files_variables_and_expansions/10-love_exponent_breath) | Raises BREATH to the power stored in LOVE. |
| [11-binary_to_decimal](init_files_variables_and_expansions/11-binary_to_decimal) | Prints BINARY as a decimal integer. |
| [12-combinations](init_files_variables_and_expansions/12-combinations) | Prints two-letter combinations except oo. |
| [13-print_float](init_files_variables_and_expansions/13-print_float) | Prints NUM to two decimal places. |
| [14-decimal_to_hexadecimal](init_files_variables_and_expansions/14-decimal_to_hexadecimal) | Prints DECIMAL in hexadecimal. |
| [2-path](init_files_variables_and_expansions/2-path) | Adds /action to PATH. |
| [3-paths](init_files_variables_and_expansions/3-paths) | Counts entries in PATH. |
| [4-global_variables](init_files_variables_and_expansions/4-global_variables) | Prints exported environment variables. |
| [5-local_variables](init_files_variables_and_expansions/5-local_variables) | Prints shell variables and functions with set. |
| [6-create_local_variable](init_files_variables_and_expansions/6-create_local_variable) | Sets BEST to School in the shell. |
| [7-create_global_variable](init_files_variables_and_expansions/7-create_global_variable) | Exports BEST with the value School. |
| [8-true_knowledge](init_files_variables_and_expansions/8-true_knowledge) | Adds 128 to TRUEKNOWLEDGE. |
| [9-divide_and_rule](init_files_variables_and_expansions/9-divide_and_rule) | Divides POWER by DIVIDE using Bash integer arithmetic. |
| [README.md](init_files_variables_and_expansions/README.md) | Notes for the exercises in this folder. |

## loops_conditions_and_parsing

| File | What it does |
| --- | --- |
| [1-for_best_school](loops_conditions_and_parsing/1-for_best_school) | Prints Best School ten times with a for loop. |
| [10-fizzbuzz](loops_conditions_and_parsing/10-fizzbuzz) | Prints 1 to 100 using FizzBuzz rules. |
| [11-read_and_cut](loops_conditions_and_parsing/11-read_and_cut) | Prints username, user ID, and home directory from /etc/passwd. |
| [12-tell_the_story_of_passwd](loops_conditions_and_parsing/12-tell_the_story_of_passwd) | Reads /etc/passwd and prints a sentence describing each account. |
| [13-lets_parse_apache_logs](loops_conditions_and_parsing/13-lets_parse_apache_logs) | Prints client IP and HTTP status from apache-access.log. |
| [14-dig_the-data](loops_conditions_and_parsing/14-dig_the-data) | Counts and sorts IP/status pairs in apache-access.log. |
| [2-while_best_school](loops_conditions_and_parsing/2-while_best_school) | Prints Best School ten times with a while loop. |
| [3-until_best_school](loops_conditions_and_parsing/3-until_best_school) | Prints Best School ten times with an until loop. |
| [4-if_9_say_hi](loops_conditions_and_parsing/4-if_9_say_hi) | Prints Best School ten times and Hi on the ninth pass. |
| [5-4_bad_luck_8_is_your_chance](loops_conditions_and_parsing/5-4_bad_luck_8_is_your_chance) | Prints different messages on the fourth and eighth passes of a loop. |
| [6-superstitious_numbers](loops_conditions_and_parsing/6-superstitious_numbers) | Prints 1 to 20 with extra messages for 4, 9, and 17. |
| [7-clock](loops_conditions_and_parsing/7-clock) | Prints hours from 0 to 12 and minutes from 1 to 59 with nested loops. |
| [8-for_is](loops_conditions_and_parsing/8-for_is) | Lists local names with the text before the first dash removed. |
| [8-for_ls](loops_conditions_and_parsing/8-for_ls) | A second copy of the local filename loop from 8-for_is. |
| [9-to_file_or_not_to_file](loops_conditions_and_parsing/9-to_file_or_not_to_file) | Checks whether school exists, is empty, and is a regular file. |

## processes_and_signals

| File | What it does |
| --- | --- |
| [0-what-is-my-pid](processes_and_signals/0-what-is-my-pid) | Prints the current script's process ID. |
| [1-list_your_processes](processes_and_signals/1-list_your_processes) | Shows processes in a tree-style ps listing. |
| [10-process_and_pid_file](processes_and_signals/10-process_and_pid_file) | Writes a PID file, handles signals, and removes the PID file on selected exit paths. |
| [11-manage_my_process,](processes_and_signals/11-manage_my_process,) | Starts, stops, or restarts manage_my_process using a PID file; the filename ends in a comma. |
| [2-show_your_bash_pid](processes_and_signals/2-show_your_bash_pid) | Finds lines containing bash in the process list. |
| [3-show_your_bash_pid_made_easy](processes_and_signals/3-show_your_bash_pid_made_easy) | Reads /proc to print process IDs whose command names contain bash. |
| [4-to_infinity_and_beyond](processes_and_signals/4-to_infinity_and_beyond) | Prints a message every two seconds until stopped. |
| [5-dont_stop_me_now](processes_and_signals/5-dont_stop_me_now) | Finds and signals running copies of 4-to_infinity_and_beyond. |
| [6-stop_me_if_you_can](processes_and_signals/6-stop_me_if_you_can) | Finds the loop process and attempts to write to its /proc entries. |
| [7-highlander](processes_and_signals/7-highlander) | Runs a loop and handles SIGTERM by printing a message. |
| [8-beheaded_process](processes_and_signals/8-beheaded_process) | Finds and sends the default kill signal to 7-highlander processes. |
| [README.md](processes_and_signals/README.md) | Notes for the exercises in this folder. |
| [manage_my_process](processes_and_signals/manage_my_process) | Appends I am alive! to /tmp/my_process every two seconds. |
