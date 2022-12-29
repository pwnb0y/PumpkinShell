# Linux Cheat Sheet
<img src="https://user-images.githubusercontent.com/88606641/209957641-5a836f6a-0767-4665-ab87-60a52e24d0e3.png" width="1000px" height="600px" />

# Introduction
Linux is a Unix-like, open source and community-developed operating system (OS) for computers, servers, mainframes, mobile devices and embedded devices. It is supported on almost every major computer platform, including x86, ARM and SPARC, making it one of the most widely supported operating systems.

# Basic Linux Commands
## Command :: 1
```
hostnamectl
```
## Description
```
Get system information including, operating system, kernel, and release version.
```

## Command :: 2
```
date
```
## Description 
```
Display the current system date and time
```

## Command :: 3
```
hostname
```
## Description
```
Display the hostname of the system
```

## Command :: 4
```
ifconfig
```
## Description
```
Display the IP and Mac Address of the system
```

## Command :: 5
```
w
```
## Description
```
Display currently logged in users in the system
```

## Command :: 6
```
free -m
```
## Description
```
Display free and used memory in the system
```

## Command :: 7
```
top
```
## Description
```
Display all running processes
```

## Command :: 8
```
ls
```
## Description
```
List all files and directories in the current working directory
```

## Command :: 9
```
ls -al
```
## Description
```
List all files and directories including, hidden files and other information like permissions, size, and owner
```

## Command :: 10
```
cd
```
## Description
```
Change the directory to the home directory
```

## Command :: 11
```
cd ..
```
## Description
```
Change the directory to one level up
```

## Command :: 12
```
cat filename
```
## Description
```
Display the content of the file
```

## Command :: 13
```
cat file1 file2 > file3
```
## Description
```
Combine two files named file1 and file2 and store the output in a new file file3
```

## Command :: 14
```
tail filename
```
## Description
```
Display the last 10 lines of a file
```

## Command :: 15
```
head filename
```
## Description
```
Display the first 10 lines of a file
```

## Command :: 16
```
mv oldfile newfile
```
## Description
```
Rename a file
```

## Command :: 17
```
rm filename
```
## Description
```
Delete a file
```

## Command :: 18
```
mkdir dirname
```
## Description
```
Create a directory
```

## Command :: 19
```
rm -rf dirname
```
## Description
```
Remove a directory
```

## Command  :: 20
```
history
```
## Description
```
Print a history list of all commands
```

## Command :: 21
```
clear
```
## Description
```
Clear the terminal
```

## Command :: 22
```
shutdown -h now
```
## Decsription
```
Shut down the system
```

## Commnad :: 23
```
reboot
```
## Description
```
Restart the system
```

# File Permission Commands
## Command :: 1
```
ls -l filename
```
## Description
```
Check the current permission of any file
```

## Command :: 2
```
chmod 777 filename
```
## Description
```
Assign full(read, write, and execute) permission to everyone
```

## Command :: 3
```
chmod -R 777 dirname
```
## Description
```
Assign full permission to the directory and all sub-directories
```

## Command :: 4
```
chmod 766 filename
```
## Description
```
Assign full permission to the owner, and read and write permission to group and others
```

## Command :: 5
```
chmod -x filename
```
## Description
```
Remove the execution permission of any file
```

## Command :: 6
```
chown username filename
```
## Description
```
Change the ownership of a file
```

## Command :: 7
```
chown user:group filename
```
## Description
```
Change the owner and group ownership of a file
```

## Command :: 8
```
chown -R user:group dirname
```
## Description
```
Change the owner and group ownership of the directory and all sub-directories
```

# User and Group Management Commands
## Command :: 1
```
w
```
## Description
```
Display all login users
```

## Command :: 2
```
useradd username
```
## Description
```
Add a new user account
```

## Command :: 3
```
userdel -r username
```
## Description
```
Delete a user account
```

## Command :: 4
```
usermod [option] username
```
## Description
```
Change the user account information including, group, home directory, shell, expiration date
```

## Command :: 5
```
usermod -aG groupname username
```
## Description
```
Add a user to a specific group
```

## Command :: 6
```
groupadd groupname
```
## Description
```
Create a new group
```

## Command :: 7
```
groupdel groupname
```
## Description
```
Remove a group
```

## Command :: 8
```
last
```
## Description
```
Display information of the last login user
```

## Command :: 9
```
id
```
## Description
```
Display UID and GID of the current user
```

# Process Management Commands
## Command :: 1
```
ps
```
## Description
```
Display all active processes
```

## Command :: 2
```
ps -ef | grep processname
```
## Description
```
Display information of specific process
```

## Command :: 3
```
top
```
## Description
```
Manage and display all processes in realtime
```

## Command :: 4
```
pstree
```
## Description
```
Display processes in the tree-like diagram
```

## Command :: 5
```
lsof
```
## Description
```
List all files opened by running processes
```

## Command :: 6
```
kill pid
```
## Description
```
Kill a specific process using process ID
```

## Command :: 7
```
killall processname
```
## Description
```
Kill all processes by name
```

## Command :: 8
```
bg
```
## Description
```
Display stopped or background jobs
```

## Command :: 9
```
pidof processname
```
## Description
```
Get the PID of any process
```

#                      Thank You

