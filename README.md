# Active Directory Home Lab (Windows Server 2025)

## Overview

This project documents a Windows Active Directory home lab built using VirtualBox.  
The lab was created to gain experience with Windows Server, Active Directory, and common help desk tasks.
The environment simulates an internal corporate network and focuses on practical troubleshooting rather than theory.

-----

## Lab Environment

- **Host machine:** i7 CPU, 16GB RAM  
- **Virtualisation:** VirtualBox  
- **Server OS:** Windows Server 2025 (Desktop Experience)  
- **Client OS:** Windows 11 Pro  
- **Domain:** `lab.local`

-----

## Network Configuration

- **Network type:** Host-only (vboxnet0)  
- **Domain Controller IP:** `192.168.56.10`  
- **Client IP:** `192.168.56.20`  
- **DNS:** Provided by the domain controller  

A host-only network was used to simulate an internal LAN and ensure reliable DNS and domain communication between machines.

-----

## Configuration Summary

- Installed Windows Server 2022  
- Promoted the server to a Domain Controller  
- Created an Active Directory domain (`lab.local`)  
- Created organisational units and test users  
- Configured static IP addressing and DNS  
- Joined a Windows 11 Pro client to the domain  
- Verified connectivity using ping and domain login  

-----

## Help Desk Tasks Practiced

- Creating and managing Active Directory user accounts  
- Resetting user passwords  
- Unlocking locked user accounts  
- Joining client machines to a domain  
- Logging in with domain credentials  
- Basic troubleshooting of domain and DNS issues  


-----

## Skills Demonstrated

- Active Directory administration  
- Windows Server installation and configuration  
- DNS and basic networking  
- Troubleshooting and problem-solving  
- First-line IT support workflows  

-----

## Examples

Screenshots of the lab setup and successful domain login can be found in the `screenshots/` folder.

Demo videos are stored in the `videos/` folder.

-----

## Notes

This lab was built for learning and portfolio purposes.  
All accounts are test users and no real personal data is used.
