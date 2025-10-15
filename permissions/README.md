# holbertonschool-shell: permissions

## Overview

This directory contains scripts focused on Linux file permissions, user and group management, and ownership tasks on Ubuntu 22.04 LTS.

You'll learn to manipulate access controls, users, groups, symbolic links, and file/directory permissions using essential commands and scripts.

---

## Requirements

- **Allowed editors:** `vi`, `vim`, `emacs`
- **Tested on:** Ubuntu 22.04 LTS
- **Script rules:**
  - Each script must be exactly two lines (`wc -l file` prints `2`)
  - Each file ends with a new line
  - First line of every script: `#!/bin/bash`
  - No use of backticks, `&&`, `||`, or `;`
  - All files must be executable

*Note:* Tasks 3, 13, 14, 15, and 16 must be performed in the sandbox for proper grading.

---

## Learning Objectives

By completing these tasks, you will understand:

- The purpose and usage of commands: `chmod`, `sudo`, `su`, `chown`, `chgrp`
- Representing file permissions for owner, group, and others as digits
- Changing permissions, owners, and groups of files and directories
- Why normal users cannot run `chown` without privilege escalation
- Running commands with root privileges and changing to superuser/user IDs
- Creating users (`adduser`, `useradd`) and groups (`addgroup`)
- Displaying user/group IDs (`id`, `groups`, `whoami`)
- Effective vs real user IDs

---

## Tasks and Scripts

| File                                   | Task Description                                                                          |
|-----------------------------------------|-------------------------------------------------------------------------------------------|
| `0-iam_betty`                          | Switch the current user to `betty`                                                        |
| `1-who_am_i`                           | Print the effective username of the current user                                          |
| `2-groups`                             | Print all groups the current user belongs to                                              |
| `3-new_owner`                          | Change ownership of file `hello` to user `betty`                                          |
| `4-empty`                              | Create an empty file called `hello`                                                       |
| `5-execute`                            | Add execute permission to the owner of `hello`                                            |
| `6-multiple_permissions`                | Add execute to owner/group, read for others on `hello`                                    |
| `7-everybody`                          | Add execute permission for owner, group, and others on `hello` (no commas allowed)        |
| `8-James_Bond`                         | Set permissions: Owner/Group = none, Others = all, on `hello` (no commas allowed)         |
| `9-John_Doe`                           | Set permissions to `-rwxr-x-wx` on `hello` (no commas allowed)                            |
| `10-mirror_permissions`                 | Set the mode of `hello` to exactly match `olleh`                                          |
| `11-directories_permissions`            | Add execute permissions for owner/group/others to all subdirectories                      |
| `12-directory_permissions`              | Create directory `my_dir` with permissions 751                                            |
| `13-change_group`                      | Change group owner of `hello` to `school`                                                 |
| `14-change_owner_and_group`             | Change owner to `vincent` and group to `staff` for all files and directories              |
| `15-symbolic_link_permissions`          | Change owner/group of symbolic link `_hello` to `vincent`/`staff`                         |
| `16-if_only`                           | Change owner of file `hello` to `vincent` only if it is owned by user `guillaume`         |

---

## Resources

- [Linux Permissions](https://intranet.hbtn.io/rltoken/UL7cEzRpzknNKTQ-3-zH2w)
- Useful man pages: `chmod`, `sudo`, `su`, `chown`, `chgrp`, `id`, `groups`, `whoami`, `adduser`, `useradd`, `addgroup`

---

## Additional Notes

- These scripts are foundational for shell users and admins to secure files and control access.
- Test scripts inside the sandbox for proper checker validation on specified tasks.
- Consult each script and man page for command options and explanations.

---

*Author: [abo-ah-md](https://github.com/abo-ah-md)*
