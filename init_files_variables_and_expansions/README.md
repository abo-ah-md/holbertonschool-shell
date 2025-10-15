# holbertonschool-shell: init_files_variables_and_expansions

## Overview

This directory contains a series of Bash scripts designed to help you understand and manipulate shell initialization files, variables, expansions, arithmetic operations, and more on Ubuntu 20.04 LTS.

Each script in this folder fulfills a specific shell task as described below. These tasks are fundamental for learning Linux shell programming and expanding your technical skills in system scripting, variable management, and shell command manipulation.

---

## Requirements

- **Allowed editors:** `vi`, `vim`, `emacs`
- **Tested on:** Ubuntu 20.04 LTS
- **Script rules:**
  - Each script must be exactly two lines (`wc -l file` should print `2`)
  - All files must end with a new line
  - The first line of all scripts: `#!/bin/bash`
  - No use of `&&`, `||`, or `;`
  - No use of `bc`, `sed`, or `awk`
  - All files must be executable

---

## Learning Objectives

By the end of this project, you should be able to:
- Explain command and file expansion (e.g., what happens when you type `ls -l *.txt`)
- Understand shell initialization files (`/etc/profile`, `/etc/profile.d`, `~/.bashrc`)
- Differentiate between local and global shell variables
- Identify and manipulate reserved variables like `HOME`, `PATH`, `PS1`
- Grasp special shell parameters (e.g., `$?`, `$!`)
- Use command substitution (`$()`, backticks ``)
- Perform shell arithmetic operations
- Create, list, and disable aliases
- Execute commands from files in the current shell

---

## Tasks and Scripts

| File | Task Description |
|------|------------------|
| `0-alias` | Create an alias named `ls` that runs `rm -f *` |
| `1-hello_you` | Print `hello user`, where `user` is the current Linux user |
| `2-path` | Add `/action` to the end of your `PATH` environment variable |
| `3-paths` | Count the number of directories in your `PATH` |
| `4-global_variables` | List all environment (global) variables |
| `5-local_variables` | List all local and environment variables, including functions |
| `6-create_local_variable` | Create a local variable named `BEST` with value `School` |
| `7-create_global_variable` | Create a global variable named `BEST` with value `School` |
| `8-true_knowledge` | Print the sum of 128 and the value stored in the environment variable `TRUEKNOWLEDGE` |
| `9-divide_and_rule` | Print the result of dividing `POWER` by `DIVIDE` (environment variables) |
| `10-love_exponent_breath` | Display `BREATH` to the power of `LOVE` (environment variables) |
| `11-binary_to_decimal` | Convert binary in environment variable `BINARY` to decimal |
| `12-combinations` | Print all possible combinations of two lowercase letters, except `oo` |
| `13-print_float` | Print a number with two decimal places from the environment variable `NUM` |
| `14-decimal_to_hexadecimal` | Convert a decimal from variable `DECIMAL` to hexadecimal |
| `15-rot13` | Encode/decode text using ROT13 encryption (ASCII-based) |
| `16-odd` | Print every other line from input, starting with the first |
| `17-water_and_stir` | Add two numbers in environment variables `WATER` and `STIR` (custom bases), print result in base `bestchol` |

---

## Resources

- [Linux shell expansions](https://intranet.hbtn.io/rltoken/qvjamZX_aoZmdZOiEapxzw)
- [Shell arithmetic](https://intranet.hbtn.io/rltoken/CuAnsjJ9mg_y-zBVwmn7mg)
- [Shell variables](https://intranet.hbtn.io/rltoken/vjgJv9-2mvkhoMT05Mk-VA)
- [Shell initialization files](https://intranet.hbtn.io/rltoken/0DxDIIG_UpoM7cKGhsuVWw)
- [Alias command](https://intranet.hbtn.io/rltoken/xiCCKpPNQRbFa1O4kvWgQA)
- [Technical Writing](https://intranet.hbtn.io/rltoken/Q8zTND7LWon8lD__raFNUw)

Refer to the following man/help pages for further info:  
`printenv`, `set`, `unset`, `export`, `alias`, `unalias`, `.`, `source`, `printf`

---

## Advanced Tasks

- **Blog:** [What happens when you type ls *.c in the terminal](https://dev.to/aboahmd/what-happens-when-you-type-ls-c-in-the-terminal-2njo)
    - Step-by-step explanation for beginners, with illustrative examples.

---

## Additional Info

- Review `/etc/profile`, `/etc/inputrc`, and `~/.bashrc` files.
- Explore `/etc/profile.d/` for profile scripts.
- You do **not** need to cover `awk`, `tar`, `bzip2`, `date`, `scp`, `ulimit`, `umask`, or advanced shell scripting yet.

---

## Directory Structure

All scripts can be found in this folder.  
Please check commit messages and individual script files for more information on implementation details.

---

*Author: [abo-ah-md](https://github.com/abo-ah-md)*
