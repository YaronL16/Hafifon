# The hitchiker's guide to the CTS
1.  Basic Linux
2.  Advanced Linux
3.  Storage
4.  Boot
5.  Package management
6.  Networks
7.  PXE and kickstart
8.  Basic Linux Security
9.  Automation
10. IT Tools
11. Identiy management
12. Time
13. Virtualization
14. Miscellaneous
15. OpenStack
16. Team specific training





# Basic Linux
### First steps
Either
- [Linux Journey](https://linuxjourney.com/)  

Or
- [Fundamentals of Red Hat Enterprise Linux redhat](https://www.edx.org/course/fundamentals-red-hat-enterprise-linux-red-hat-rh066x)

### Navigation
- `pwd`
- `ls`
- `tree`
- `cd`
- `exit`

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





# Advanced Linux
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





# Storage
### HDD vs SSD
- Difference between the two
- nvme
- SATA
- m.2

### Partitions
- Partition types (Primary and Secondary)
- `fdisk`
- `parted`
- `partprobe`
- `partx`

### Filesystems
- Types of filesystems
- GPT
- MBR

### Raids
- All types of raids

### LVM
- All lvm





# Boot
- Bios
- UEFI
- grub2
- `dracut`
- /boot/*
- The boot process
- Single user mode





# Package management
### RPM
- `rpm`

### YUM
- Listing
- Searching
- Dependencies
- History
- Rollback

### Repositories
- Create a repository





# Networks
### Hardware
- Cables
- Transceivers
- Hubs
- Bridges
- Switches
- Routers

### Sniffers
- `wireshark`
- `tcpdump`

### Networking files in Linux
- /etc/hosts
- /etc/resolv.conf
- /etc/sysconfig/network
- /etc/sysconfig/network-scripts/*

### Layer 2
- MAC addresses
- Frames
- VLANs
- 802.1q (VLAN tagging)
- Broadcast domains
- Collision domains

### Layer 3
- IP addresses
- Subnets
    - Class subnets
    - CIDR subnets
- Static routes
- Protocols
    - ARP
    - ICMP
- Routing schemes
    - Unicast
    - Broadcast
    - Multicast
    - Anycast
    - Geocast
- Packets

### Layer 4
- TCP
- UDP

### Network commands
- `arping`
- `ping`
- `traceroute`
- `ifconfig`
- `ifup`
- `ifdown`
- `ip`
- `nmcli`
- `nmtui`
- `netstat`
- `ss`
- `nmap`

### DHCP
- DHCP flow
- DHCP server
- `dhclient`
  
### DNS
- DNS server
- `dig`
- `host`

### Bonds and teams
- Bonds
- Teams
- LACP





# PXE and kickstart
### PXE boot
- PXE server

### Kickstart
- Anaconda





# Basic Linux Security
### iptables
- netfilter
- `iptables`

### firewalld
- `firewalld`
- NAT with firewalld

### SELinux
- Everything about SELinux





# Automation
### Bash
- bash

### Ansible
- Ansible





# IT Tools
### Apache
- httpd

### HAProxy
- haproxy

### Keepalived
- keepalived





# Identiy management
### LDAP
- ldap

### Kerberos
- kerberos

### IPA
- freeipa





# Time
### ntp
- ntp
- ntpd
- chronyd

### Daylight saving time
- DST





# Virtualization
### Virtual network
- bridges
- ovs
- different virtual nic types

### Containers
- namespace
- cgroups
- Linux containers
- Docker
  - Docker volumes type
  - Docker networks
  - Docker images





# Miscellaneous
- Git





# OpenStack
- Openstack services
- Devstack deployment
- Openstack CLI