# Shell, Permissions — SEIP Project Part 1

## 📚 Project Overview
This project introduces essential Linux shell commands for managing file permissions, ownership, and user groups. By completing these tasks, you'll gain hands-on experience with access control and system administration basics.

## 🎯 Learning Objectives
By the end of this project, you should be able to:
- Explain file permission values and symbolic representations
- Modify file permissions using `chmod`
- Change file ownership with `chown`
- Manage group ownership using `chgrp`
- Identify current user and group with `id`, `whoami`, and `groups`
- Create and manage users and groups using `adduser`, `useradd`, and `addgroup`

## 🛠️ Commands to Know
- `chmod` — change file permissions
- `chown` — change file owner
- `chgrp` — change group ownership
- `id`, `whoami`, `groups` — identify user and group info
- `adduser`, `useradd`, `addgroup` — create users and groups
- `sudo`, `su` — execute commands with elevated privileges

## ✅ Task List

| Task # | Title               | Description                                      |
|--------|---------------------|--------------------------------------------------|
| 0      | My name is Betty    | Create a file and rename it                     |
| 1      | Who am I            | Display current user                            |
| 2      | Groups              | Show user’s groups                              |
| 3      | New owner           | Change file owner                               |
| 4      | Empty!              | Create an empty file                            |
| 5      | Execute             | Add execute permission                          |
| 6      | Multiple permissions| Set multiple permissions at once                |
| 7      | Everybody!          | Give all users full access                      |
| 8      | James Bond          | Set specific permissions (execute only)         |
| 9      | John Doe            | Change owner and group                          |
| 10     | Look in the mirror  | Display file permissions                        |
| 11     | Directories         | Create a directory                              |
| 12     | More directories    | Create nested directories                       |
| 13     | Change group        | Modify group ownership                          |
| 14     | Owner and group     | Change both owner and group                     |
| 15     | Symbolic links      | Create symbolic links                           |
| 16     | If only             | Apply conditional permissions                   |

## 📎 Resources
- [Linux File Permissions](https://linuxize.com/post/understanding-linux-file-permissions/)
- `man` pages: `chmod`, `chown`, `chgrp`, `id`, `groups`, `whoami`, `adduser`, `useradd`, `addgroup`

## 🧠 Tips
- Use `ls -l` to inspect file permissions.
- Numeric permissions: `r=4`, `w=2`, `x=1`. Add them to get values like `755`, `700`, etc.
- Symbolic permissions: `chmod u+x filename` adds execute for user.
- Practice with dummy files before applying changes to important ones.

## 🚀 Final Goal
Be able to explain and apply shell permission concepts confidently—without relying on Google. You’ve got this!

