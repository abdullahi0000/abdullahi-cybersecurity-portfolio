# Network Intrusion Detection System (NIDS)

## Project Overview
This project involves setting up and configuring a Network Intrusion Detection System (NIDS) using **Security Onion**. The objective was to detect and monitor malicious activities in a simulated lab environment.

## Objectives
- Configure a secure lab environment.
- Deploy Security Onion for intrusion detection.
- Simulate attacks using Kali Linux on Metasploitable.
- Monitor and analyze intrusion alerts.

## Project Components
- **Security Onion**: NIDS deployment and monitoring.
- **Kali Linux**: Attack simulation tools (e.g., Metasploit, Nmap).
- **Metasploitable**: Vulnerable target machine.

## Project Setup
- IP Configurations:
  - Security Onion: `192.168.253.10`
  - Kali Linux: `192.168.253.129`
  - Metasploitable: `192.168.253.128`
- VMware Workstation Pro was used to host the virtual machines.

## Key Features
- Snort Rules for detecting specific attacks.
- Bro/Zeek integration for network traffic analysis.
- Kibana for visualizing intrusion alerts.

## Results
- Successfully detected and logged attacks such as:
  - Brute Force (via Hydra).
  - Remote Exploit (via Metasploit).
  - Port Scanning (via Nmap).

## Conclusion
This project demonstrated the effectiveness of Security Onion as a NIDS for monitoring and detecting intrusions in a simulated lab environment.

## Screenshots
(Include screenshots of your Security Onion alerts, attacks, or setup.)

## References
- [Security Onion Documentation](https://securityonion.net/docs/)
- [Metasploit Basics](https://metasploit.help/)

---

