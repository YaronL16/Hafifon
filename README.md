# The hitchiker's guide to the CTS
1.  Basic Linux
2.  Storage
3.  Boot
4.  Package management
5.  Networks
6.  PXE and kickstart
7.  Basic Linux Security
8.  Automation
9.  IT Tools
10. Identiy management
11. Time
12. Virtualization
13. Miscellaneous
14. OpenStack
15. Team specific training





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
- Hardware RAID
- Software RAID

### LVM
- All lvm





# Boot
- Bios
- UEFI
- grub2
- `dracut`
- /boot/*
- initramfs
- initrd
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
- MTU

### Layer 3
- IP addresses
- Subnets
    - Class subnets
    - CIDR subnets
    - Reserved network addresses
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
- squid

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
- Timezones





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
- SSL/TLS and certificates





# OpenStack
- Openstack services
- Devstack deployment
- Openstack CLI