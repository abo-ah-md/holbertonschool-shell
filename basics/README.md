## Shell, Basics

This folder contains scripts that cover the following foundational skills:

- What is a shell, the terminal, and the shell prompt?
- Navigating and listing files and directories with commands (`cd`, `ls`, `pwd`)
- Understanding hidden files, home directories, and root directories
- File operations: copying (`cp`), moving (`mv`), removing (`rm`), creating directories (`mkdir`)
- Symbolic and hard links (`ln`)
- Wildcards for batch operations
- Basic command utilities (`type`, `which`, `help`, `man`)
- Reading `man` pages and common bash shortcuts

---

### Task Overview

| File | Description |
| :--- | :--- |
| `0-current_working_directory` | Print the absolute path of the current working directory. |
| `1-listit` | List the contents of the current directory. |
| `2-bring_me_home` | Change to the user's home directory (without using shell variables). |
| `3-listfiles` | List directory contents in long format. |
| `4-listmorefiles` | List all files, including hidden ones, in long format. |
| `5-listfilesdigitonly` | Same as above, but with numerical UIDs/GIDs and including hidden files. |
| `6-firstdirectory` | Create a directory named `/tmp/my_first_directory`. |
| `7-movethatfile` | Move the file `betty` to `/tmp/my_first_directory`. |
| `8-firstdelete` | Delete the file `betty` in `/tmp/my_first_directory`. |
| `9-firstdirdeletion` | Delete the directory `/tmp/my_first_directory`. |
| `10-back` | Change to the previous working directory. |
| `11-lists` | List all files in the current, parent, and `/boot` directories. |
| `12-file_type` | Display the file type of `/tmp/iamafile`. |
| `13-symbolic_link` | Create a symbolic link to `/bin/ls` named `__ls__`. |
| `14-copy_html` | Copy HTML files to the parent directory only if they are newer or don't exist. |
| `15-lets_move` | Move all files starting with an uppercase letter to `/tmp/u`. |
| `16-clean_emacs` | Delete all files ending with `~`. |
| `17-tree` | Create a directory tree: `welcome/to/school`. |
