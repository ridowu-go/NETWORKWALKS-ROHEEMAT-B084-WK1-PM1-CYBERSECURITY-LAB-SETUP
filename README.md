# NETWORKWALKS-ROHEEMAT-B084-WK1-PM1-CYBERSECURITY-LAB-SETUP


# Cybersecurity Lab Setup - Week 1

## Overview
Set up a virtual cybersecurity lab using VirtualBox with Kali Linux and a second VM and verified connectivity between them.

## Tools Used
- VirtualBox
- Kali Linux

## Steps

### 1. Install VirtualBox
Downloaded and installed VirtualBox on Windows.

### 2. Create NAT Network
- Opened VirtualBox > Tools > Network
- Created a new NAT Network
- Enabled DHCP

### 3. Set Up Kali Linux VM
- Imported / installed Kali Linux
- Attached it to the NAT Network
- Started the VM and verified it boots correctly

### 4. Set Up Second VM
- Created a second VM
- Attached it to the same NAT Network
- Started the VM

### 5. Verify Connectivity
- Checked IP address on the VMs using ip a
- Tested connectivity using `ping`