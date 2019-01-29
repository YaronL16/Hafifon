# Basic Linux


### First steps

Start with an introduction to Linux, use:  
Either
- [Linux Journey](https://linuxjourney.com/)  

Or
- [Fundamentals of Red Hat Enterprise Linux redhat](https://www.edx.org/course/fundamentals-red-hat-enterprise-linux-red-hat-rh066x)

### Navigation

Make sure the trainee understands how to use the following commands:
- `pwd`
- `ls`
- `tree`
- `cd`
- `exit`


**Tasks:**

**Questions:**

- **Q**: How can I see hidden files? **A**: `ls -a`
- **Q**: How can I see file sizes in human readable formats? **A**: `ls -h`
- **Q**: How can I change directory to my home? **A**: `cd ~`
- **Q**: How can I change directory to the previous current directory? **A**: `cd -`
- **Q**: How can I change directory to the parent directory? **A**: `cd ..`
- **Q**: What would happen if my current directory is the root directory and I use the command `cd ..`? **A**: Nothing

### Vimtutor
- `vimtutor`

### Keyboard shorcuts
- Learn terminal keyboard shorcuts

### RTFM
- `man`

### Text manipulation
- `echo`
- `cat`
- `grep`
- `cut`
- `uniq`
- `sort`
- `wc`
- `head`
- `tail`
- `awk`
- `sed`

### Basic file manipulation
- `cp`
- `mv`
- `rm`
- `which`
- `locate`
- `find`

### IO redirection and Pipes
- Redirecting STDIN
- Redirecting STDOUT
- Redirecting STDERR
- Pipes
- `xargs`

### Users and groups
- `whoami`
- `id`
- users
- `useradd`
- `usermod`
- groups
- `groupmod`
- `passwd`
- /etc/passwd
- /etc/shadows
- /etc/group
- `sudo`
- `su`
- /etc/sudoers
- `visudo`

### File permissions
- `chmod`
- `chown`
- `chgrp`
- Sticky bit
- `umask`
- `getfacl`
- `setfacl`

### Monitoring
- `ps`
- `top`
- `free`
- `du`
- `df`
- `lsof`
- `uname`

### Logging
- /var/log/*
- journalctl
- dmesg

### Archives
- `tar`
- `gzip`
- `unzip`

### Environment variables
- `env`
- PATH
- HOME

### Home directory
- .bashrc
- .bash_profile
- .bash_history

### FHS
- Filesystem Hierarchy Standard

### Processes
- /proc
- /run

### Services
- Runlevels
- Sysv
- Systemd

### Timed tasks
- Crontab
- At

### SSH
- `ssh`
- `ssh-keygen`
- `ssh-copy-id`
- `scp`
- SSH tunnels (Local, Remote and Dynamic)