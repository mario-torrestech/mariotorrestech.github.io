# Mario Torres
Security operations and testing homelab documentation.

[About Me / Professional Background](about.md)

# 🎯 Overview
A dedicated cybersecurity learning environment for penetration testing and security operations, serving as both practical infrastructure and a comprehensive training platform.

# 🎓 Current Path
* Actively pursuing [PNPT (Practical Network Penetration Tester)](https://certifications.tcm-sec.com/pnpt/) certification
* Building security testing environments
* Hands-on experience with security tools and techniques

# 🖥️ Infrastructure
Core Hardware (Intel NUC8 Hades Canyon)
* Intel Core i7-8709G with Radeon RX Vega M GH
* 64GB DDR4 RAM
* Storage: 250GB SSD (OS/Tools), 1TB SSD (Lab/Testing)

Testing Environments
* Active Directory Lab (In Progress)
  * Windows Server security testing infrastructure
  * Enterprise attack/defense scenarios
  * AD vulnerabilities and misconfigurations testing
* Kali Linux Environment
  * Security testing VM
  * Penetration testing suite
  * Network analysis tools

Production Infrastructure
* Proxmox VE 8.0 Hypervisor
  * Segmented networks
  * Isolated test environments
  * Concurrent lab operations
* Containers: Proxmox LXCs and Docker

# 🔒 Security Implementation
* Network Segmentation
  * VLAN 1: Production
  * VLAN 2: IoT (Isolated)
  * VLAN 3: Guest (Zero-trust)
  * Lab Networks (Isolated)
* Controls & Monitoring
  * Pi-hole: DNS filtering
  * NGINX Proxy Manager: SSL/traffic inspection
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