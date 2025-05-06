1. Introduction to Linux
What is Linux? (Kernel vs OS)

History and distributions (Ubuntu, CentOS, Debian, Arch)

Open Source philosophy (GNU, FSF, Linux Foundation)

Linux vs Unix

2. Linux System Architecture
Kernel space vs User space

System call interface

Init system (systemd, init, upstart)

Daemons and services

3. Linux Installation & Boot Process
BIOS/UEFI and GRUB

Bootloader stages

/boot, initramfs, and kernel loading

Runlevels/targets

Systemd target units

4. Command Line Basics
Shells (bash, zsh, sh, etc.)

Navigation: cd, ls, pwd, file

File operations: cp, mv, rm, touch, mkdir, find, locate

Redirection & piping: >, >>, <, |, tee

Wildcards and globbing

5. File System Hierarchy
Linux directory structure: /, /home, /etc, /var, /usr, /tmp, etc.

File types: regular, directory, block, character, symbolic links

Hard vs soft links

Mounting filesystems: mount, umount, fstab

6. Permissions & Ownership
File permissions: r, w, x

chmod, chown, chgrp

Numeric vs symbolic modes

umask and default permissions

SUID, SGID, sticky bit

7. User & Group Management
Creating users/groups: useradd, groupadd, passwd

Modifying and deleting: usermod, userdel

/etc/passwd, /etc/shadow, /etc/group

Sudo and privilege escalation

8. Process Management
Understanding processes: PID, PPID, UID

Foreground/background: &, jobs, fg, bg

Process tools: ps, top, htop, nice, renice, kill, pkill

Signals: SIGINT, SIGKILL, SIGTERM, etc.

9. Package Management
Debian-based
apt, dpkg, apt-get, apt-cache

RedHat-based
yum, dnf, rpm

Repositories, PPA, GPG keys

10. Networking in Linux
ip, ifconfig, ip a, ip r

ping, traceroute, netstat, ss, nmap

/etc/hosts, /etc/resolv.conf, /etc/network/interfaces

Services: SSH, HTTP, DNS basics

Firewall: iptables, ufw, firewalld

11. Disk Management
Partitioning tools: fdisk, parted

Formatting: mkfs.ext4, mkfs.xfs

Mounting & unmounting

LVM: PV, VG, LV, snapshots

df, du, lsblk, blkid

12. Shell Scripting
#!/bin/bash shebang

Variables, arrays, strings

Conditionals: if, case

Loops: for, while, until

Functions, exit codes

Reading input, file I/O

13. Logging & Monitoring
System logs: /var/log, syslog, journalctl

Log rotation: logrotate

Monitoring tools: vmstat, iostat, iotop, sar, dstat

Audit logs: auditd, ausearch, aureport

14. Security Basics
SSH keys, config hardening

File integrity: aide, tripwire

SELinux, AppArmor

User access controls

fail2ban, tcpwrappers

15. Advanced Topics
Crontab and scheduling

NFS, SMB, FTP

Kernel modules: lsmod, modprobe

Chroot and jail environments

Linux Containers basics: chroot, cgroups, namespaces

16. Linux in the Cloud & DevOps
Running Linux on cloud platforms (AWS EC2, GCP, Azure)

Docker fundamentals

Systemd unit files for services

CI/CD tools on Linux (Jenkins, GitHub Actions)

17. Practice Labs & Scenarios
Set up a LAMP stack

Automate backup with rsync and cron

Configure a basic firewall

Write a monitoring script

Create and run a custom systemd service


