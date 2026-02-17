# Learn-Linux-With-Me

🐧 Linux Operating System – Learning Journey

![eb2e374d16ac252a868ad39426b17e00](https://github.com/user-attachments/assets/176ee0f2-7e55-4883-96a9-858e36fc8ac5)


 # Overview
This repository documents my hands-on learning journey of the Linux Operating System, covering core concepts, command-line proficiency, system administration fundamentals, networking, security, and automation.

Linux is the backbone of modern cloud computing, DevOps, cybersecurity, and backend infrastructure. Through structured study and practical labs, I am building strong foundational skills required for Cloud Engineering and Systems Administration roles.

# Learning Objectives

- Understand Linux architecture and system components
- Master essential and advanced Linux CLI commands
- Manage files, processes, users, and permissions
- Configure networking and services
- Secure Linux systems
- Automate tasks using Bash scripting
- Prepare for cloud-based Linux environments (e.g., AWS EC2)

# What is Linux?
Linux is an open-source, Unix-like operating system kernel originally created by Linus Torvalds (1991). It powers:

- Cloud infrastructure
- Web servers
- DevOps pipelines
- Containers (Docker/Kubernetes)
- Cybersecurity tools
- Embedded systems
- Supercomputers
- Popular distributions include:
- Ubuntu
- CentOS / Rocky Linux
- Debian
- Kali Linux
- Red Hat Enterprise Linux

# Linux Architecture
Linux consists of:

1. Kernel – Core of the OS, manages hardware & system calls
2. Shell – Command interpreter (e.g., Bash)
3. File System – Hierarchical directory structure
4. System Utilities – Core commands and services
5. User Applications

# Linux File System Structure
Key directories:
/          → Root directory
/home      → User home directories
/etc       → Configuration files
/var       → Logs & variable data
/bin       → Essential user binaries
/sbin      → System binaries
/usr       → User applications
/tmp       → Temporary files

# Command Line Mastery
File & Directory Management
pwd        → Print working directory
ls         → List files
cd         → Change directory
mkdir      → Create directory
rm         → Remove files
cp         → Copy files
mv         → Move/rename files
touch      → Create file

# Viewing & Editing Files
cat        → View file contents
less       → Scroll through file
nano       → Text editor
vi / vim   → Advanced editor
head       → First lines
tail       → Last lines

# User & Permission Management
User Commands
whoami
useradd
passwd
usermod
groupadd

# File Permissions
chmod
chown
chgrp
Permission structure:
r = read
w = write
x = execute
eg, chmod 755 file.sh

# Process & System Management
top        → Monitor processes
ps         → Process status
kill       → Terminate process
htop       → Advanced process viewer
systemctl  → Manage services
eg. systemctl start nginx
systemctl enable nginx

# Networking in Linux
ip a
ifconfig
ping
netstat
ss
curl
wget
Understanding:

IP addressing
DNS
Ports
Firewalls
SSH

# Linux Security Fundamentals

- File permissions & ownership
- SSH key authentication
- Firewall configuration (ufw / firewalld)
- Disabling root login
- Log monitoring (/var/log)
- Basic hardening practices

# Bash Scripting
Automating tasks using shell scripts:
eg, #!/bin/bash
echo "System Info:"
uname -a
df -h
Concepts learned:
Variables
Conditionals
Loops
Functions
Cron jobs (task scheduling)

# Linux in the Cloud

- Hands-on experience includes:
- Launching Linux EC2 instances
- Connecting via SSH
- Installing packages
- Configuring web servers
- Managing storage
- Securing cloud-based Linux servers

Linux is critical in:

- AWS
- Azure
- Google Cloud
- Kubernetes environments

# Tools & Environments Used

- VirtualBox / VMware
- Ubuntu Server
- AWS EC2
- Git & GitHub
- VS Code
- Windows Subsystem for Linux (WSL)

# Learning Resources

- Official Linux documentation
- Linux man pages (man command)
- Online labs
- Cloud-based sandbox environments
- Practice projects

# Practical Projects Completed

- User management lab
- File permission lab
- Basic firewall configuration
- Web server setup (Apache/Nginx)
- Bash automation script
- Log analysis task
- SSH configuration and hardening

# Skills Gained

✔ Command-line proficiency
✔ Linux system administration fundamentals
✔ Security best practices
✔ Cloud Linux deployment
✔ Troubleshooting & log analysis
✔ Automation using Bash

 # Future Goals

- Advanced Bash scripting
- Linux networking deep dive
- Containers (Docker)
- Kubernetes fundamentals
- Infrastructure as Code
- Linux for Cybersecurity

Prepare for:

- Linux Essentials
- RHCSA
- CompTIA Linux+

# Conclusion
Learning Linux has strengthened my foundation in Cloud Engineering, DevOps, and Cybersecurity. Mastery of the command line and system-level operations is essential for managing modern infrastructure environments.
This repository reflects my continuous learning and hands-on practice as I progress toward becoming a Cloud Engineer.
