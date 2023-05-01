---
title: General Optimizations
linktitle: General Optimizations
toc: true
type: book
date: '2019-05-05T00:00:00+01:00'
draft: false
summary: General optimizations to do first.
# Prev/next pager order (if `docs_section_pager` enabled in `params.toml`)
weight: 10
---


## Do Not Disable 
- Xbox 
- UWP 
- UAC 
- Wi-Fi
- Windows Firewall
- Microsoft Store 
- FSO and Game Bar 


> **Note** 
> Checkpoint #1
> At this point there should probably be around ~60 processes 

## GameUtil
*kills desktop window manager which removes 1 frame of lag, locks*  
- Move to desktop
- go to gameutil first then load game
- Disable Idle
  
## [LatencyMon](https://www.resplendence.com/latencymon)

## Install Steam
- Login and start downloading game 
- Configure controller 
- Install games 
- Right click the steam shortcut -> Properties and enter this command:

```bash
"C:\Program Files (x86)\Steam\Steam.exe" -no-browser +open steam://open/minigameslist
```

## Intelligent Standby List Cleaner 

## [MSI Tool](https://forums.guru3d.com/threads/windows-line-based-vs-message-signaled-based-interrupts-msi-tool.378044/)


## [Calypto's Latency Guide](calypto.us)
- Open Powershell in Administrator Mode 
- bcedit /set disabledynamictick yes 
- Device Manager 

## Melody Low Latency Script 
- Basic Tweaks 
- bcedit commands
> **Note**
> Add Melody tweak commands here at some point so they can be copied and pasted easily.
