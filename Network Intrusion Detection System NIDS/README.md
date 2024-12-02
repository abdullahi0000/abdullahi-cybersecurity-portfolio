# Network Intrusion Detection System (NIDS)

## Project Overview

In this project, I will set up a NIDS using **Security Onion** deployed in VMware Workstation Pro. To test it, I will perform a few attacks on a vulnerable machine, Metasploitable, using Kali Linux. Security Onion will monitor the traffic between the virtual machines and is expected to generate alerts if any intrusions occur.

## Objectives
- Configure a secure lab environment.
- Deploy Security Onion for intrusion detection.
- Simulate attacks using Kali Linux on Metasploitable.
- Monitor and analyze intrusion alerts.

## Project Components
- **Security Onion**: NIDS deployment and monitoring.
- **Kali Linux**: Attack simulation tools (e.g., Metasploit, Nmap).
- **Metasploitable**: Vulnerable target machine.


## Network set up
![Network Diagram](https://github.com/abdullahi0000/abdullahi-cybersecurity-portfolio/blob/main/Drawing.png?raw=true)


## Project Setup
Security Onion requires two network interfaces for proper setup: one for management, configured on NAT with an IP address to access the web interface, and another for sniffing, configured on Host-Only without an IP address. To enable Security Onion to sniff and monitor traffic effectively, other virtual machines must also use the Host-Only network. For example, Kali Linux should have two network interfaces—one on NAT (optional) and the other on Host-Only—while Metasploitable should be set to Host-Only.
- IP Configurations:
  - Security Onion: `192.168.19.140` on NAT 
  - Kali Linux: `192.168.128.19` on NAT, `192.168.189.130` on Host only
  - Metasploitable: `192.168.189.129` on Host only
- VMware Workstation Pro was used to host the virtual machines.







## Conclusion
This project demonstrated the effectiveness of Security Onion as a NIDS for monitoring and detecting intrusions in a simulated lab environment.

## Screenshots
(Include screenshots of your Security Onion alerts, attacks, or setup.)

## References
- [Security Onion Documentation](https://securityonion.net/docs/)
- [Metasploit Basics](https://metasploit.help/)

