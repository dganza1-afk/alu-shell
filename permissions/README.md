# Permissions

Shell scripts covering Linux file permissions, ownership and user/group management.

| Script | Description |
| --- | --- |
| `0-iam_betty` | Switches the current user to the user `betty` |
| `1-who_am_i` | Prints the effective username of the current user |
| `2-groups` | Prints all the groups the current user is part of |
| `3-new_owner` | Changes the owner of the file `hello` to the user `betty` |
| `4-empty` | Creates an empty file called `hello` |
| `5-execute` | Adds execute permission to the owner of the file `hello` |
| `6-multiple_permissions` | Adds execute permission to the owner and the group owner, and read permission to other users, for `hello` |
| `7-everybody` | Adds execute permission to the owner, the group owner and other users for `hello` |
| `8-James_Bond` | Sets `hello` to no permissions for owner and group, all permissions for other users |
| `9-John_Doe` | Sets the mode of `hello` to `-rwxr-x-wx` |
| `10-mirror_permissions` | Sets the mode of `hello` to the same mode as `olleh` |
| `11-directories_permissions` | Adds execute permission to all subdirectories of the current directory for owner, group and others |
| `12-directory_permissions` | Creates a directory `my_dir` with permissions 751 |
| `13-change_group` | Changes the group owner of `hello` to `school` |
| `14-change_owner_and_group` | Changes owner to `vincent` and group owner to `staff` for all files and directories in the working directory |
| `15-symbolic_link_permissions` | Changes the owner and group owner of the symbolic link `_hello` to `vincent` and `staff` |
| `16-if_only` | Changes the owner of `hello` to `vincent` only if it is owned by `guillaume` |
