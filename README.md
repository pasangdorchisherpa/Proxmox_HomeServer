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
![pihole.md](docs/pihole.md)

- Network-wide DNS server
- Blocks ads, trackers, and unsafe domains
- Provides visibility into network DNS activity

---

### Minecraft Server — Local VM
![minecraft-server.md](docs/minecraft-server.md)

- Linux-based Minecraft server
- Runs internally on the home network
- External access provided via VPN only

---

### 🪟 Windows Virtual Machine
![windows-vm.md](docs/windows-vm.md)

- Windows VM for learning IT administration
- User management, permissions, and file access
- Safe sandbox for testing system changes

---

## 🛣️ Roadmap & Future Plans
![roadmap.md](docs/roadmap.md)

Planned additions include:
- WireGuard VPN for secure remote access
- TrueNAS VM for centralized storage and backups
- Nextcloud for private file and photo sharing
- Improved monitoring, backups, and automation

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
