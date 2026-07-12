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

## 6. Verification Results

<img width="587" height="180" alt="Screenshot 2026-07-12 032542" src="https://github.com/user-attachments/assets/103c8d8a-1484-4381-9151-05d9baedb172" />

## 7. What I Learned

I learned how to install Ubuntu Server on the correct disk and connect to it remotely using SSH. I also learned that the server can run without a monitor after startup. I kept the operating system and future storage on separate disks to make the environment easier to manage.

## 8. Result

Ubuntu Server was installed successfully and can now be managed from my laptop using SSH.
