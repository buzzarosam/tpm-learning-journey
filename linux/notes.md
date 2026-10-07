# Linux learning 

## What I learned

Linux is an operating system used extensively in servers and infrastructure.

## File system and Navigation

~ - the current user's home directory
/ - th root for the Linux filesystem
.. - the parent directory
/mnt/c - access to the windows C: drive from WSL

For my WSL environment:
~ = /home/salim

## Commands
pwd - print working directory
ls - list files
ls -l - list files with detailed information
cd - change directory
cd .. - move to the parent directory
mkdir - make directory

## Permissions
Linux permissions are commonly represented using:

r - read
w - write
x - execute 

The first character indicates the type 
d - directory
- - regular file

Permissions are associated with the owner, group, and others.

## Git
Git is version control system used to track chages to the file

Basic Workflow:

Working directory
      ↓
git add
      ↓
Staging area
      ↓
git commit
      ↓
Git repository
      ↓
git push
      ↓
GitHub


## Processes 

A process is a running instance of a program.

Every running process has a unique Process ID (PID).

ps - show processes associated with the current terminal
ps aux - show detailed information about running processes
sleep 60 & - run sleep as a background process

Important process concepts:
PID - unique process identifier
CPU - processor usage
MEM - memory usage
root - Linux superuser


 
