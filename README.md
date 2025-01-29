# Scalable and Secure Network Infrastructure for Distributed Offices


## Course Information
- **Course:** Building Networked Systems Security (**EP2520**), KTH Royal Institute of Technology  
- **Date:** March 2023  

## Project Overview
This project focuses on designing and implementing a secure enterprise network infrastructure with VPN-based remote access, identity-based authentication, intrusion detection, and access control mechanisms. The system provides secure, encrypted communication across distributed office branches while ensuring real-time monitoring and network security enforcement.  

## Key Features & Implementations
- Secure Remote Access: Implemented OpenVPN site-to-site and remote-access tunneling for encrypted communication between office branches.  
- Authentication System: Deployed FreeRADIUS for certificate-based authentication, ensuring only verified devices and users can access internal resources.  
- Intrusion Detection System (IDS): Configured SNORT-based IDS to log and analyze network traffic, detecting potential security threats.  
- Secure Web Services: Integrated Nextcloud for encrypted file sharing and communication, protected with Two-Factor Authentication (2FA).  
- Reverse Proxy & Firewalls: Implemented Nginx reverse proxy and OpenWRT firewalls to restrict unauthorized access and enforce security policies.  
- Secure DNS & DDoS Protection: Configured Cloudflare DoH for secure DNS resolution and enabled firewall-based DDoS protection.  

## Technologies & Tools Used  
The project integrates various security and networking tools to create a robust network architecture:  
- Networking & VPN: OpenVPN, OpenWRT, iptables  
- Authentication & Access Control: FreeRADIUS, Certificate Authority (CA)  
- Intrusion Detection & Monitoring: SNORT IDS, Wireshark  
- Web Security & Data Protection: Nginx Reverse Proxy, Nextcloud (Secure File Exchange)  
- Containerization & Virtualization: Docker, LXD (Linux Containers)  
- Firewall & Security Hardening: OpenWRT, iptables, TCP SYN flood protection  
- Domain Security: Cloudflare DoH (DNS over HTTPS), DNSSEC  

## Outcomes  
- Designed and implemented a scalable network security architecture suitable for enterprise environments.  
- Established a site-to-site VPN and remote access VPN to enable secure connectivity across locations.  
- Integrated multi-factor authentication and certificate-based access control for enhanced security.  
- Deployed a real-time intrusion detection system, improving network monitoring and response capabilities.  
- Secured internal web services and communication through encrypted channels and strong access controls.  

## Repository Contents
BNSS_report.pdf contains detailed report of the whole project

## Repository & Access Notes  
Scripts and specific configurations are not included due to KTH course guidelines.  

