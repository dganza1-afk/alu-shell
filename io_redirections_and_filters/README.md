# I/O Redirections and Filters

Shell scripts covering standard input/output redirection and text filtering commands.

| Script | Description |
| --- | --- |
| `0-hello_world` | Prints `Hello, World` followed by a new line |
| `1-confused_smiley` | Displays the confused smiley `"(Ôo)'` |
| `2-hellofile` | Displays the content of `/etc/passwd` |
| `3-twofiles` | Displays the content of `/etc/passwd` and `/etc/hosts` |
| `4-lastlines` | Displays the last 10 lines of `/etc/passwd` |
| `5-firstlines` | Displays the first 10 lines of `/etc/passwd` |
| `6-third_line` | Displays the third line of the file `iacta` |
| `7-file` | Creates a file with a heavily escaped name containing `Best School` |
| `8-cwd_state` | Writes the result of `ls -la` into the file `ls_cwd_content` |
| `9-duplicate_last_line` | Duplicates the last line of the file `iacta` |
| `10-no_more_js` | Deletes all regular `.js` files in the current directory and subfolders |
| `11-directories` | Counts the directories and sub-directories in the current directory |
| `12-newest_files` | Displays the 10 newest files, newest first |
| `13-unique` | Prints only the words from input that appear exactly once, sorted |
| `14-findthatword` | Displays lines containing `root` from `/etc/passwd` |
| `15-countthatword` | Counts the lines containing `bin` in `/etc/passwd` |
| `16-whatsnext` | Displays lines containing `root` plus the 3 lines after them |
| `17-hidethisword` | Displays the lines of `/etc/passwd` that do not contain `bin` |
| `18-letteronly` | Displays the lines of `/etc/ssh/sshd_config` starting with a letter |
| `19-AZ` | Replaces `A` with `Z` and `c` with `e` from input |
| `20-hiago` | Removes all `c` and `C` characters from input |
| `21-reverse` | Reverses its input |
| `22-users_and_homes` | Displays all users and their home directories, sorted by user |
| `23-empty_casks` | Lists the names of all empty files and directories, recursively |
| `24-gifs` | Lists all `.gif` files recursively, without their extension, sorted case-insensitively |
| `25-acrostic` | Decodes an acrostic using the first letter of each line |
| `26-the_biggest_fan` | Displays the 11 hosts/IPs with the most requests from a TSV log |
