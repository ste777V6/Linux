# Linux Commands

Welcome to the Linux Commands Reference repository! This collection is designed to help beginners and experienced users explore and understand essential Linux commands. Whether you're troubleshooting, scripting, or just learning, these commands will help you navigate the Linux ecosystem.

### 📖 Contents
The repository includes folders and files grouped by categories of Linux commands:

---


- 1 Navigate the file system : move through the filesystem and view the content of a file
- 2 Manage file content in Bash : Commands for creating, deleting, copying, and moving files.
- 3 Filter content: find files and context of files and filter
- 4 Manage users and permissions : change users permission and groups
- 5 Get help in Linux :  Find info about commands
- 6 System Monitoring: Tools to monitor system performance, resource usage, and processes.
- 7 Networking: Basic and advanced commands for managing networks and connections.
- 8 Permissions: Managing file ownership and access control.
- 9 Package Management: Installing, removing, and managing software packages.
- 10 Disk Usage: Commands for analyzing disk space and managing partitions.
- 11 Scripting Basics: Useful one-liners and examples for bash scripting.

### Learn and Test:
Open the files to view command explanations and examples.
Run the commands in a Linux terminal to see them in action.

Folder Structure

linux-commands/

├── navigate the file system/
│   ├── pwd show the current position in the filesystem
│   ├── ls list the file in the current position
│   ├── cat print the content of a file in the shell
│   ├── head show the first 10 rows of a file
│   ├── tail show the last 10 rows of a file

├── manage file content in Bash
│   ├── cp copy a file or directory
│   ├── mkdir create an empty directory
│   ├── mv move a file or directory
│   ├── nano open or creates files inthe nano editor
│   ├── rm remove a file
│   ├── rmdir remove an empty directory
│   ├── touch create a file

├── filter content
│   ├── find search for directory and files that meet specific criteria
│   ├── grep search a specific string in a file
│   ├── I (piping) Send the standar output of a command as standard input of the next command

├── manage users and permissions/
│   ├── chmod change permission on files and directories
│   ├── chown change ownership of a files and directories
│   ├── groupdel delete a group from the system (use with sudo)
│   ├── useradd add user to the system (use with sudo)
│   ├── userdel delete user from the system (use with sudo)
│   ├── usermod modify existing user (use with sudo)

├── get help in Linux
│   ├── apropos search the man for a specific string
│   ├── man show the command full description
│   ├── whatis show 1 row command description

├── package-management/
│   ├── apt
│   ├── yum
│   ├── dnf

├── disk-usage/
│   ├── df
│   ├── du
│   ├── lsblk

├── scripting-basics/
│   ├── bash-loops
│   ├── file-handling
│   ├── variables

├── system-monitoring/
│   ├── top
│   ├── htop
│   ├── ps

├── networking/
│   ├── ping
│   ├── netstat
│   ├── ssh
