<code>

## Linux System Hardening
https://tryhackme.com/room/linuxsystemhardening

**Physical Security**
Adding a password to GRUB is a reasonable measure to block users with physical access to a system’s keyboard from gaining access.

**Filesystem Partitioning and Encryption**
There are various software systems and tools that provide encryption to Linux systems. Since many modern Linux distributions ship with LUKS (Linux Unified Key Setup)

**Firewall**
Netfilter, iptables, nftables, ufw

**Remote Access**
Password sniffing
Password guessing and brute-forcing
Exploiting the listening service

**Securing User Accounts**
Use sudo
Disable root
Enforce a Strong Password Policy

**Software and Services**
Disable Unnecessary Services
Block Unneeded Network Ports
Avoid Legacy Protocols
Remove Identification Strings

**Update and Upgrade Policies**
t is vital that you keep your system updated with the latest security patches and bug fixes.

You can update a Debian-based distribution, such as Ubuntu, with the following two commands:

apt update to download package information from the configured sources
apt upgrade to install available upgrades for all packages from the configured sources
You can update a RedHat or Fedora system using the following:

dnf update on newer releases (Red Hat Enterprise Linux 8 and later)
yum update on older rele

**Audit and Log Configuration**

<code>
