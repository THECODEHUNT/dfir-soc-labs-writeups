# Nmap Scanning Basics — Practice Lab

## Overview
This lab focuses on using Nmap for network scanning to identify live hosts, open ports, and running services.

## What is Nmap?
Nmap (Network Mapper) is a powerful tool used for network discovery and security auditing.

## Objectives
- Discover live hosts
- Identify open ports
- Detect running services
- Understand basic scanning techniques

## Commands Used

### 1. Basic Scan
```bash
nmap 192.168.1.1
Scans the most common ports on the target.

2. Service Version Detection
nmap -sV 192.168.1.1

Detects services running on open ports.

3. Aggressive Scan
nmap -A 192.168.1.1

Includes OS detection, version detection, script scanning, and traceroute.

4. Scan Specific Ports
nmap -p 80,443 192.168.1.1

Scans only selected ports.

5. Scan Entire Network
nmap 192.168.1.0/24

Scans all devices in the network range.

Findings
Identified open ports such as 22 (SSH), 80 (HTTP)
Detected running services and versions
Observed how different scan types reveal different levels of detail
Key Learning

Nmap is essential for both attackers and defenders. In DFIR, it helps understand exposed services and possible attack surfaces.

Screenshots
Basic Scan Output

Service Detection

Aggressive Scan
