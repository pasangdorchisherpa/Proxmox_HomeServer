# Proxmox_HomeServer Overview

This directory contains documentation for my **Proxmox VE homelab**.  
Each document describes a service or virtual machine I run, how it is set up, and its purpose within my home server environment.

The goal of this homelab is to learn virtualization, networking, system administration, and secure self-hosting practices.

---

## Platform

- **Hypervisor:** Proxmox VE
- **Environment:** Home server / private network
- **Access:** Proxmox Web UI and VM console
- **Security Model:** Internal services + VPN-based access (planned)

---

## Documented Services & VMs

### Pi-hole — DNS & Network Filtering
[Pihole](docs/pihole.md)

- Network-wide DNS server
- Blocks ads, trackers, and unsafe domains
- Provides visibility into network DNS activity

---

### Minecraft Server — Local VM
[Minecraft-Server](docs/minecraftserver.md)

- Linux-based Minecraft server
- Runs internally on the home network
- External access provided via VPN only

---

### Windows Virtual Machine
[Windows-VM](docs/IT_windows_VM.md)

- Windows VM for learning IT administration
- User management, permissions, and file access
- Safe sandbox for testing system changes

---

### Tailscale — Secure VPN / Tunnel
**Tailscale**
- WireGuard-based mesh VPN
- Secure remote access to internal services
- Used to expose select home server services without port forwarding
- Enables access to the homelab from external networks with minimal configuration

---

### ☁️ Nextcloud — Private File Sharing & NAS
**Nextcloud**
- Self-hosted file storage and transfer
- Acts as a personal NAS and file-sharing platform
- Accessible only via VPN for security

**Real-world validation:**
- Successfully tested long-distance file transfers with a remote user in **Nepal**
- Confirms cross-continental accessibility, encryption, and reliability
- Other home server services are also accessible remotely via Tailscale, with expected latency

---

## Roadmap & Future Plans
[Roadmap](docs/roadmap.md)

Planned additions include:
- TrueNAS VM for centralized storage and backups
- Improved monitoring, backups, and automation
- Automated backups and snapshots
  
---

## Goals of This Homelab

- Gain hands-on experience with:
  - Virtualization
  - Networking & DNS
  - Linux & Windows administration
  - Secure service hosting
- Build a documented, expandable home infrastructure
- Practice real-world system administration concepts

---

## Notes

This homelab is a **learning environment**, not a production system.  
Configurations may change frequently as new services are added and tested.
