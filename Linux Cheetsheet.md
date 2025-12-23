
##  Basic Linux Command Reference Cheat Sheet

| Command             | Description                                           |
| ------------------- | ----------------------------------------------------- |
| `man <tool>`        | Opens the manual page for the specified tool.         |
| `<tool> -h`         | Displays the help page of the tool.                   |
| `apropos <keyword>` | Searches man pages for a given keyword.               |
| `cat`               | Concatenates and prints file contents.                |
| `whoami`            | Displays the current logged-in username.              |
| `id`                | Returns the user ID (UID) and group ID (GID).         |
| `hostname`          | Shows or sets the system's hostname.                  |
| `uname`             | Prints system information (use `-a` for all details). |
| `pwd`               | Prints the current working directory.                 |

---

## 🌐 Network & System Info

| Command    | Description                                                |
| ---------- | ---------------------------------------------------------- |
| `ifconfig` | Displays or configures network interfaces (deprecated).    |
| `ip`       | Manages IP addresses, routes, interfaces, and tunnels.     |
| `netstat`  | Displays network connections and routing tables.           |
| `ss`       | Modern replacement for `netstat`, shows socket statistics. |
| `ps`       | Displays currently running processes.                      |
| `who`      | Shows who is currently logged in.                          |
| `env`      | Prints the environment variables.                          |
| `lsblk`    | Lists block devices.                                       |
| `lsusb`    | Lists USB devices.                                         |
| `lsof`     | Lists open files.                                          |
| `lspci`    | Lists PCI devices.                                         |

---

## 👤 User & Group Management

| Command    | Description                                    |
| ---------- | ---------------------------------------------- |
| `sudo`     | Runs a command as another user (usually root). |
| `su`       | Switches to another user account.              |
| `useradd`  | Creates a new user.                            |
| `userdel`  | Deletes a user account and associated files.   |
| `usermod`  | Modifies a user account.                       |
| `addgroup` | Adds a group to the system.                    |
| `delgroup` | Deletes a group from the system.               |
| `passwd`   | Changes user password.                         |

---

## 📦 Package Management

| Command    | Description                                          |
| ---------- | ---------------------------------------------------- |
| `dpkg`     | Installs, removes, and manages `.deb` packages.      |
| `apt`      | High-level package manager for Debian-based systems. |
| `aptitude` | Alternative to `apt`, with a text UI.                |
| `snap`     | Installs and manages Snap packages.                  |
| `gem`      | Ruby package manager.                                |
| `pip`      | Python package manager.                              |

---

## 🛠 System Services & Processes

| Command      | Description                                        |
| ------------ | -------------------------------------------------- |
| `systemctl`  | Controls systemd services.                         |
| `ps`         | Lists running processes.                           |
| `journalctl` | Views logs from systemd journal.                   |
| `kill`       | Sends signals to processes (like `kill -9 <PID>`). |
| `bg`         | Resumes a suspended job in the background.         |
| `jobs`       | Lists background jobs.                             |
| `fg`         | Brings a job to the foreground.                    |

---

## 🌍 Networking Tools

| Command                  | Description                                                |
| ------------------------ | ---------------------------------------------------------- |
| `curl`                   | Transfers data to/from a server (supports many protocols). |
| `wget`                   | Retrieves files using HTTP, HTTPS, or FTP.                 |
| `python3 -m http.server` | Starts a quick web server on port 8000.                    |

---

## 📁 File & Directory Management

| Command | Description                            |
| ------- | -------------------------------------- |
| `ls`    | Lists directory contents.              |
| `cd`    | Changes directory.                     |
| `clear` | Clears the terminal.                   |
| `touch` | Creates an empty file.                 |
| `mkdir` | Creates a new directory.               |
| `tree`  | Displays directories in tree format.   |
| `mv`    | Moves or renames files or directories. |
| `cp`    | Copies files or directories.           |
| `nano`  | Command-line text editor.              |
| `which` | Shows the path of a command.           |

---

## 🔍 File Searching & Viewing

| Command    | Description                                 |
| ---------- | ------------------------------------------- |
| `find`     | Searches files in a directory hierarchy.    |
| `updatedb` | Updates the file index used by `locate`.    |
| `locate`   | Finds files quickly using a prebuilt index. |
| `more`     | Views output one screen at a time.          |
| `less`     | Like `more`, but with more features.        |
| `head`     | Shows the first 10 lines of a file.         |
| `tail`     | Shows the last 10 lines of a file.          |

---

## 🧹 Text Processing

| Command  | Description                                        |
| -------- | -------------------------------------------------- |
| `sort`   | Sorts lines in text files.                         |
| `grep`   | Searches for patterns in files or input.           |
| `cut`    | Removes sections from each line.                   |
| `tr`     | Translates or deletes characters.                  |
| `column` | Formats output into columns.                       |
| `awk`    | Pattern scanning and text processing tool.         |
| `sed`    | Stream editor for filtering and transforming text. |
| `wc`     | Counts lines, words, and characters in a file.     |
| `chmod`  | Changes file permissions.                          |
| `chown`  | Changes file owner and group.                      |

---
