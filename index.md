[About Me / Professional Background](about.md)

## 📋 Executive Summary
A dedicated homelab environment built for hands-on learning in cybersecurity, with a current focus on [PNPT (Practical Network Penetration Tester) certification](https://certifications.tcm-sec.com/pnpt/) This environment serves as both a practical learning platform and a foundation for developing real-world security testing experience.

## 🖥️ Infrastructure Overview

### Core Hardware
- **Primary Server**: Intel NUC8 Hades Canyon
  - Intel i7-8709G with Radeon Graphics
  - 64GB RAM
  - Storage Configuration:
    - System Drive: 250GB SSD (OS/Tools)
    - Lab Environment: 1TB SSD (Testing/VM Storage)

### Virtualization Environment
- **Hypervisor**: Proxmox VE 8.0
  - Efficient resource management
  - Snapshot capabilities for system recovery
  - Virtual networking configuration

### Core Services
1. **Infrastructure Services**
   - Pi-hole for DNS and network-wide ad blocking
   - Step-CA running in Docker for internal certificate authority
   - Nginx Proxy Manager for internal service routing

2. **Security Learning Environment**
   - Dedicated Kali Linux instance
   - Active Directory testing lab for PNPT study:
     - Windows domain environment
     - Attack and defense scenarios
     - Isolated network segment for safe testing
   - Currently studying security testing tools and methodologies
   - Focusing on PNPT certification preparation

3. **Containerized Services**
   - Docker implementations including:
     - Step-CA for certificate management
     - yt-dlp for media management
   - Learning container security fundamentals

## 🛡️ Network Architecture

### Network Segmentation

| Network | Purpose | Description |
|---------|----------|-------------|
| Production | Core Services | Houses infrastructure services (Pi-hole, Step-CA, Nginx) |
| Admin | Management | Administrative access and management |
| Testing Lab | Security Testing | Isolated environment containing AD lab and security testing resources |

### Access Control
- Isolated internal network - no external exposure
- Kali instance with controlled access to Admin and Testing environments
- Network segmentation for service isolation
- Internal PKI using Step-CA signed certificates

### AD Lab Environment
- Dedicated network segment for Active Directory testing:
  - Windows domain environment for PNPT preparation
  - Kali Linux used as attack machine, Windows 11/Windows Server
  - Isolated from production services
  - Focused on AD attack and defense scenarios

### Web Application Security Lab
- **OWASP Testing Environment**
 - OWASP Juice Shop with Burp Suite and FoxyProxy setup
 - Hands-on experience with key vulnerabilities:
   - SQL Injection and authentication attacks
   - Data exposure and XXE vulnerabilities 
   - Access control and security misconfigurations
   - Cross-Site Scripting (XSS) techniques
   - Component security assessment
  - Focus on identification, exploitation, and remediation fundamentals
  - Implementing proper testing methodology and documentation

### Infrastructure Services

#### Certificate Management
- Step-CA deployment in Docker
- Internal certificate authority
- Learning PKI fundamentals and implementation

#### DNS and Ad Blocking
- Pi-hole providing:
  - Local DNS resolution
  - Network-wide ad blocking
  - Query logging and monitoring
  - Custom filtering capabilities

#### Service Routing
- Nginx Proxy Manager for:
  - Internal service routing
  - SSL termination
  - Access control

## 🔬 Current Learning Focus

### 1. Certification Preparation
- Actively pursuing [PNPT (Practical Network Penetration Tester)](https://certifications.tcm-sec.com/pnpt/) certification- Active Directory attack methodologies
- Windows domain security testing
- Building practical testing experience in isolated lab environment

### 2. Infrastructure Management
- Service deployment and maintenance
- Network security implementation
- System hardening practices

### 3. Skill Development
- Security testing fundamentals
- Network security concepts
- Infrastructure automation basics

## 🛠️ Tools & Technologies

### Core Infrastructure
- Proxmox VE
- Docker
- Pi-hole
- Step-CA
- Nginx Proxy Manager

### Security Tools
- Kali Linux
- Currently learning:
  - Security testing methodologies
  - Common security tools
  - Network analysis fundamentals

### Development & Automation
- Basic Bash scripting
- Service configuration
- Infrastructure management

---
*Last Updated: November 2024*  
[About Mario Torres](about.md)