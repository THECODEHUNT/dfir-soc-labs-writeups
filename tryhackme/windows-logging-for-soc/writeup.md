# Windows Logging for SOC — TryHackMe Writeup

## Overview
This room focuses on understanding Windows Event Logs and how SOC analysts use them to detect attacks.

## Key Concepts Learned
- Windows Event Logs (Security, System, Application)
- Event ID 4624 (Successful login)
- Event ID 4625 (Failed login)
- Logon Type 10 (RDP login)
- Brute force detection using logs

## Investigation Summary
- Identified brute force attack from IP: 10.10.53.248
- Compromised user: Administrator
- Detected malicious RDP login using Logon Type 10

## Tools Used
- Event Viewer
- TryHackMe Lab VM

## Key Learning
Logs are the backbone of SOC operations. Understanding Event IDs helps detect real attacks like brute force and unauthorized access.

## Screenshots
(Add screenshots here later)
