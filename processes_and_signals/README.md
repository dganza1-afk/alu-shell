# Processes and signals

Shell scripts covering Linux processes, PIDs and signals.

| Script | Description |
| --- | --- |
| `0-what-is-my-pid` | Displays its own PID |
| `1-list_your_processes` | Displays all running processes in a user-oriented format with their hierarchy |
| `2-show_your_bash_pid` | Displays the processes whose lines contain the word `bash` |
| `3-show_your_bash_pid_made_easy` | Displays the PID and name of processes whose name contains `bash`, without using `ps` |
| `4-to_infinity_and_beyond` | Displays `To infinity and beyond` indefinitely, sleeping 2 seconds between lines |
| `5-dont_stop_me_now` | Stops the `4-to_infinity_and_beyond` process using `kill` |
| `6-stop_me_if_you_can` | Stops the `4-to_infinity_and_beyond` process without using `kill` or `killall` |
| `7-highlander` | Displays `To infinity and beyond` indefinitely and `I am invincible!!!` when receiving `SIGTERM` |
| `67-stop_me_if_you_can` | Sends `SIGTERM` to the `7-highlander` process |
