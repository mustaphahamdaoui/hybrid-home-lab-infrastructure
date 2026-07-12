# Day 001 — Ubuntu Server Installation

## 1. Goal

Install Ubuntu Server on the home lab machine, configure remote SSH access, and verify that the server is ready for future infrastructure labs.

## 2. Starting Situation

Before this lab:

- The old PC was not configured as a server.
- Ubuntu Server was not installed.
- Remote SSH access was not available.
- The machine contained two disks:
  - 128 GB SSD
  - 1 TB HDD

## 3. Hardware Used

- Device type: Old gaming PC
- RAM: 8 GB
- System disk: 128 GB Kingston SSD
- Secondary disk: 1 TB HDD
- Network connection: Ethernet
- Installation media: USB flash drive
- Administration device: Laptop

## 4. Installation Decisions

### Operating System Disk

I installed Ubuntu Server on the 128 GB SSD.

Reason:

SSD provides faster boot and system performance.


### Secondary Storage

I left the 1 TB HDD untouched during installation.

Reason:

Write the reason in your own words.

Example ideas:

Separating the operating system from lab data makes recovery easier.

### Filesystem

I used a simple Linux filesystem layout on the SSD.

### Ubuntu Pro

I skipped Ubuntu Pro during installation because it was not required for the initial home lab setup.

### OpenSSH

I selected OpenSSH Server during installation so that the server could be managed remotely from my laptop.

### Extra Server Packages

I did not install additional server snaps during installation.

Reason:

I wanted to start with a clean server and install services manually later so that I can understand each component.

## 5. Hostname

The configured hostname is:

homelab-server-01
<img width="587" height="180" alt="image" src="https://github.com/user-attachments/assets/47f792e0-d367-4234-9147-41001500867b" />
