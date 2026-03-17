# Vulnerability Analysis - Week 3

This lab is part of the Vulnerability Analysis subject.

Objective:
To connect to the PwnTillDawn network and scan for vulnerable machines.

Tools Used:
- Kali Linux
- OpenVPN
- Nmap

Steps:
1. Download the PwnTillDawn connection pack
2. Connect using OpenVPN
3. Scan the network using Nmap
4. Identify active machines in the network

Connect to VPN
openvpn PwnTillDawn.ovpn

Scan network
nmap 10.150.150.0/24

Check active hosts
nmap -sn 10.150.150.0/24

# Vulnerability Analysis Report

Target Network
10.150.150.0/24

Scanning Tool
Nmap

Command Used
nmap 10.150.150.0/24

Result
Several hosts were detected as active in the network.

Example Target
IP Address: 10.150.150.69
Operating System: Windows
Status: Active

Conclusion
Network scanning successfully identified multiple hosts within the range.
These hosts may contain vulnerabilities for further penetration testing.
