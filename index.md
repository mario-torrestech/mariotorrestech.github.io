# Mario Torres
Security operations and testing homelab documentation.

[About Me / Professional Background](about.md)

# 🎯 Overview
A dedicated cybersecurity learning environment for penetration testing and security operations, serving as both practical infrastructure and a comprehensive training platform for the PNPT (Practical Network Penetration Tester) certification and other personal projects.

# 🎓 Current Path
* Actively pursuing [PNPT (Practical Network Penetration Tester)](https://certifications.tcm-sec.com/pnpt/) certification
* Building security testing environments in Linux and Windows
* Hands-on experience with security tools and techniques

# 🖥️ Infrastructure

## Core Hardware
Intel NUC8 Hades Canyon
* Intel Core i7-8709G with Radeon graphics
* 64GB RAM
* Storage: 250GB SSD (OS/Tools), 1TB SSD (Lab/Testing)

## Lab Environment
Proxmox VE 8.0 Hypervisor managing:

**PNPT Training Lab**
* Active Directory Environment
* Kali Linux for penetration testing
* Isolated virtual network segment for security testing

**Personal Services**
* Various containerized applications (Docker)
* Mix of LXC containers and VMs
* Media management and automation tools

# 🔒 Security Implementation
* Network Segmentation
  * VLAN 1: Production
  * VLAN 2: IoT (Isolated)
  * VLAN 3: Guest (Zero-trust)
  * Lab Networks (Isolated)
* Controls & Monitoring
  * Pi-hole: DNS filtering
  * NGINX Proxy Manager: SSL/port forwarding
  * Step-ca: Certificate management
  * Tailscale: VPN access and logging

# 💾 Storage & Backup
* Synology DS920+ (2x 8TB SHR)
* Backblaze B2 off-site backup

# 📚 Development Roadmap
* Complete PNPT certification
* Enhance AD lab with attack vectors
* Implement SIEM solution
* Automate security testing/response
* Document findings and practices