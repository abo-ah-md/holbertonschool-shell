# holbertonschool-shell: io_redirections_and_filters

## Overview

This directory contains Bash scripts and utilities designed to help you understand shell I/O redirection, filters, special characters, and common file operations on Ubuntu 20.04 LTS.

Each script solves a specific shell task to develop your skills in manipulating standard input, output, files, pattern matching, sorting, and text processing.

---

## Requirements

- **Allowed editors:** `vi`, `vim`, `emacs`
- **Tested on:** Ubuntu 20.04 LTS
- **Script rules:**
  - Each script must be exactly two lines (`wc -l file` should print `2`)
  - All files must end with a new line
  - The first line in each script: `#!/bin/bash`
  - No use of backticks, `&&`, `||`, or `;`
  - Do not use `sed` or `awk`
  - All files must be executable

---

## Learning Objectives

By completing these scripts, you should be able to:
- Describe and use shell redirections and filters
- Redirect standard output and input to/from files, and combine commands with pipes
- Use commands like `head`, `tail`, `cat`, `wc`, `sort`, `uniq`, `grep`, `tr`, `rev`, `cut`, `find`
- Handle white spaces, quotes, backslashes, pipes, command separators, tilde, and comments
- Understand the format of `/etc/passwd` and `/etc/shadow` files

---

## Tasks and Scripts

| File                     | Task Description                                                                                  |
|--------------------------|--------------------------------------------------------------------------------------------------|
| `0-hello_world`          | Print “Hello, World”, followed by a new line                                                     |
| `1-confused_smiley`      | Display a confused smiley `"(Ôo)'`                                                               |
| `2-hellofile`            | Display the content of `/etc/passwd`                                                             |
| `3-twofiles`             | Display the contents of `/etc/passwd` and `/etc/hosts`                                           |
| `4-lastlines`            | Display the last 10 lines of `/etc/passwd`                                                       |
| `5-firstlines`           | Display the first 10 lines of `/etc/passwd`                                                      |
| `6-third_line`           | Display the third line of the file `iacta` (in current dir)                                      |
| `7-file`                 | Create a file with a complex name containing `Best School` text                                  |
| `8-cwd_state`            | Save the result of `ls -la` to the file `ls_cwd_content`                                         |
| `9-duplicate_last_line`  | Duplicate the last line of `iacta` file (in current dir)                                         |
| `10-no_more_js`          | Delete all regular `.js` files in current directory and subfolders                               |
| `11-directories`         | Count the number of directories and subdirectories in current directory (excluding . and ..)     |
| `12-newest_files`        | Display the 10 newest files in current directory, one per line                                   |
| `13-unique`              | Print only words from input that appear exactly once (sorted)                                    |
| `14-findthatword`        | Show lines in `/etc/passwd` containing “root”                                                    |
| `15-countthatword`       | Count lines in `/etc/passwd` containing “bin”                                                    |
| `16-whatsnext`           | Display lines containing “root” and the 3 following lines from `/etc/passwd`                     |
| `17-hidethisword`        | Display all lines in `/etc/passwd` that do NOT contain “bin”                                     |
| `18-letteronly`          | Display lines of `/etc/ssh/sshd_config` starting with a letter                                   |
| `19-AZ`                  | Replace all “A” with “Z” and “c” with “e” from input                                             |
| `20-hiago`               | Remove all “c” and “C” from input                                                                |
| `21-reverse`             | Reverse input                                                                                   |
| `22-users_and_homes`     | Display all users and home directories, sorted by user, from `/etc/passwd`                       |
| `23-empty_casks`         | Find all empty files and directories in current dir and subdirs                                  |
| `24-gifs`                | List all `.gif` files in current dir and subdirs (names only, sorted, case-insensitive)          |
| `25-acrostic`            | Decode acrostic using the first letter of each line from input                                   |
| `26-the_biggest_fan`     | Show the 11 hosts/IPs that made the most requests in TSV log files (NASA webserver log example)  |

---

## Resources

- [Shell, I/O Redirection](https://intranet.hbtn.io/rltoken/dJRc-mwT3vNw7SCWZNlGcg)
- [Special Characters](https://intranet.hbtn.io/rltoken/k2EzFVxAXrpfJMvl8-1ukQ)
- Useful man pages: `echo`, `cat`, `head`, `tail`, `find`, `wc`, `sort`, `uniq`, `grep`, `tr`, `rev`, `cut`, `passwd (5)`

---

## Special Notes

- All examples in these scripts use real or typical system files as input/output.
- Many tasks are classic shell and Unix exercises used to strengthen fundamentals.

---

## More Info

- Review your `/etc/passwd` and `/etc/shadow` files for real-world examples of file formats.
- No need to learn about `fmt`, `pr`, `du`, `gzip`, `tar`, `lpr`, `sed`, or `awk` yet.

---

*Author: [abo-ah-md](https://github.com/abo-ah-md)*
