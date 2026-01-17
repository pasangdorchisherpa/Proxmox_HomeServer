# Nextcloud — Private Cloud Storage (LXC)

## Overview

This homelab runs **Nextcloud** inside a **Linux Container (LXC)** on Proxmox VE to provide private, self-hosted file storage and sharing.

The service functions as a personal cloud and NAS replacement, offering features similar to Google Drive while keeping full control over data, access, and security.

All access to Nextcloud is restricted to authenticated users via a private VPN connection.

---

## Why Nextcloud?

Nextcloud was chosen to:

- Replace third-party cloud storage services
- Maintain full ownership of personal data
- Enable secure file sharing across long distances
- Integrate cleanly into an existing Proxmox-based homelab

Running Nextcloud in an LXC provides:
- Lightweight resource usage
- Fast startup and recovery
- Easy backups and snapshots
- Strong isolation from the Proxmox host

---

## Real-World Usage

This Nextcloud instance is actively shared with my girlfriend, who is located in **Nepal**.

We use it as our primary cloud storage solution instead of Google Drive for:

- Secure file storage
- Long-distance file transfers
- Sharing sensitive personal documents
- Media synchronization across devices

Despite the geographic distance, the service has proven to be:
- Reliable
- Consistently accessible
- Secure
- Performant with expected international latency

This real-world usage validated the setup beyond a simple lab experiment.

---

## Access & Security

- Nextcloud is **not publicly exposed**
- Access is only possible through a private VPN
- No open ports or public endpoints
- User authentication is required
- Data is encrypted in transit

This approach significantly reduces the attack surface while maintaining ease of use for trusted users.

---

## Core Features Used

- File storage and folder sharing
- User-based access control
- Cross-device access (desktop & mobile)
- Reliable uploads and downloads
- Secure data transfers over encrypted connections

Advanced features are added gradually as the homelab evolves.

---

## Infrastructure Details

- Platform: Proxmox VE
- Virtualization: Linux Container (LXC)
- Storage: Local / attached storage managed by Proxmox
- Network: Private internal network with VPN-only access

---

## Screenshots


![i1]{../Screenshots/NextcloudHomeScreen.png}
![i2]{../Screenshots/NextcloudServer.png}

---

> This service is part of a personal homelab and not a production environment.  
