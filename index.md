# Security Operations & Testing Homelab

## 🎯 Overview
A dedicated learning environment focused on cybersecurity, penetration testing, and security operations. This lab serves as both a practical infrastructure and a comprehensive security learning platform where I actively develop my cybersecurity skills.

## 🎓 Current Security Learning Path
- Actively pursuing PNPT (Practical Network Penetration Tester) certification
- Building and maintaining security testing environments
- Developing hands-on experience with security tools and techniques

## 🖥️ Infrastructure 

### Core Hardware
- Primary Server: Intel NUC8i7HNK1 (Hades Canyon)
  - CPU: Intel Core i7-8709G with Radeon RX Vega M GH graphics
  - RAM: 64GB DDR4 
  - Storage: 
    - 250GB SSD (OS and Security Tools)
    - 1TB SSD (Lab Environments and Testing)

### Testing Environments
- Active Directory Lab Environment (In Progress)
  - Windows Server infrastructure for security testing
  - Simulated enterprise environment for attack/defense scenarios
  - Testing common AD vulnerabilities and misconfigurations
- Kali Linux Environment
  - Dedicated VM for security testing
  - Penetration testing tools suite
  - Network analysis capabilities

### Production Infrastructure
- Hypervisor: Proxmox VE 8.0
  - Segmented virtual networks
  - Isolated testing environments
  - Resource management for concurrent lab operations
- Container Platforms:
  - Proxmox LXCs for system services
  - Docker for application containers

## 🔒 Security Implementation

### Network Security Architecture
- Networking:
  - Router: Unifi Cloud Gateway
- Network Segmentation:
  - VLAN 1: Main network (Production systems)
  - VLAN 2: IoT devices (Isolated)
  - VLAN 3: Guest network (Zero-trust)
  - Lab Networks: Isolated security testing environments

### Security Controls
- Network Security Monitoring:
  - Pi-hole for DNS-level threat detection and filtering
  - NGINX Proxy Manager for SSL termination and traffic inspection
  - Step-ca for certificate lifecycle management
  - Tailscale VPN for encrypted remote access and activity logging

## 🔄 In Progress Projects
- Active Directory Security Lab:
  - Building test domain infrastructure
  - Implementing security controls
  - Creating attack and defense scenarios
- SIEM Implementation:
  - Evaluating security monitoring solutions
  - Planning log aggregation infrastructure
  - Designing alert frameworks
- Basic System Monitoring:
  - Custom Grafana dashboards

## 💾 Backup & Storage
- Synology DS920+ NAS (2x 8TB drives in SHR)
- Backblaze B2 for off-site backup
- Regular backup testing and verification

## 📚 Professional Development & Roadmap

### Current Focus
- Pursuing PNPT certification with emphasis on:
  - Network penetration testing methodology
  - Active Directory security architecture
  - Attack surface analysis and defense
  - Security monitoring and incident response

### Next Steps
- Enhance AD lab environment with attack vectors and monitoring
- Implement SIEM solution for centralized security monitoring
- Develop automation for security testing and response
- Document findings and establish best practices
- Create detailed documentation of findings