---
# Title, summary, and page position.
linktitle: Installation
summary: How to install fgcOS.
weight: 30
icon: book
icon_pack: fas

# Page metadata.
title: Installation
type: book # Do not modify.
created: 2023-04-23
updated: 2023-04-23 10:30
share: true
---

## Install Windows  

- Disable internet 
- Do video call
- Reboot 
- Press F11 to get into the BIOS select UEFI drive 
	- Custom Drive 
- Move old Windows install to Windows.old
	- Select Windows 10 install 
	- Do not connect to the internet 
	- Continue with limited setup
- Create user account and password 
- Click next 

> **Warning**
> Make sure you're not connected to the internet before rebooting so it doesn't try to connect to install updates 

- Connect to the internet 
- Install AnyDesk for remote administration *not necessary for a self-install*
- Disable Windows Security Processes  
	- Windows Antivirus 
	- Real-time protection 
	- Cloud-delivered protection 
	- Automatic sample submission 
	- Tamper Protection 
- Install Windows updates *don't do anything else while it's updating*

---

## Install ReviOS
- AME Wizard 
- install ReviOS via playbook file
- It will likely reboot a few times. 
---