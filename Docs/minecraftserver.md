# Minecraft Server (Local VM)

## Overview

This Minecraft server runs inside a **Ubuntu virtual machine** hosted on Proxmox VE.  
It is designed primarily for **local network play**, with optional access through a VPN for trusted external users.

---

## Setup Summary

- Ubuntu Server VM running on Proxmox VE
- Minecraft server managed as a system service
- Allocated dedicated CPU and memory resources
- Server runs continuously in the background

---

## Network Design

### Internal Access
- Server is accessible to devices on the home network
- No public port forwarding exposed to the internet

### VPN-Based External Access
- Friends can join the server **only through a VPN**
- Prevents exposing the server directly to the public internet
- Improves security and control over who can connect

---

## Use Case in My Home Server

- Provides a private game server for learning:
  - Linux server management
  - Service monitoring
  - Resource allocation
- Demonstrates safe self-hosting practices
- Acts as a real-world workload to monitor VM performance

---

## What I’ve Learned

- Managing long-running services on Linux
- Monitoring CPU, memory, and disk usage
- Network isolation and access control
- Using Proxmox tools to troubleshoot VM performance

---

## Planned Enhancements

- Automated backups
- Performance tuning
- Server management scripts


## Screenshots

![i3](Screenshots/minecraftserver_summary.png)
![i1](Screenshots/minecraftserver_console.png)
![i2](Screenshots/minecraftserver_hardware.png)
