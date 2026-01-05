# Pi-hole (DNS & Network Filtering)

## Overview

Pi-hole is deployed in my Proxmox VE homelab as a **dedicated DNS server** for my home network.  
Its primary purpose is to block advertisements, trackers, and unsafe or unwanted domains **before** they reach client devices.

Rather than running ad blockers on individual devices, Pi-hole provides **network-wide filtering**.

---

## Setup Summary

- Deployed as a virtual machine in Proxmox VE
- Assigned a static local IP address
- Configured as the primary DNS server on the home network
- Managed through the Pi-hole web admin dashboard

---

## How I Use Pi-hole

### DNS Resolution
- Acts as the main DNS resolver for devices on my home network
- All DNS queries pass through Pi-hole before reaching upstream DNS providers

### Ad & Tracker Blocking
- Uses blocklists to prevent connections to:
  - Ad servers
  - Tracking domains
  - Known malicious or unsafe sites
- Reduces ads across browsers, mobile devices, and smart devices

### Network Visibility & Control
- Provides insight into:
  - DNS query volume
  - Top queried domains
  - Blocked requests
- Useful for learning how devices communicate on a network

---

## Use Case in My Home Server

- Improves browsing experience by reducing ads
- Adds a layer of network-level security
- Centralized DNS management instead of per-device solutions
- Serves as a foundation for future services like VPN-based remote access

---

## Future Improvements

- Integrate Pi-hole with WireGuard VPN
- Add custom blocklists and allowlists
- Configure secondary DNS for redundancy

---

## Screenshot

![Image](main/Screenshots/pi-hole.png)
