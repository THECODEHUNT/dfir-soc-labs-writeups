# Phishing Analysis — TryHackMe Writeup

## Overview
This room focuses on identifying phishing attacks by analyzing emails, links, and headers. The goal is to understand how attackers trick users using social engineering and how to detect such attempts.

## Key Concepts Learned
- Phishing and social engineering
- Email spoofing
- Suspicious links and domains
- Email header analysis
- Indicators of compromise (IOCs)

## What is Phishing?
Phishing is a cyber attack where attackers impersonate legitimate entities (like banks, companies, or services) to steal sensitive information such as passwords, OTPs, or financial data.

## Common Phishing Indicators
- Urgent or threatening language (e.g., "Your account will be blocked!")
- Suspicious sender email (looks similar but not exact)
- Mismatched URLs (hover shows different link)
- Attachments from unknown sources
- Poor grammar or unusual formatting

## Email Header Analysis
Email headers help trace the origin of an email. Important fields:
- **From** → Sender address (can be spoofed)
- **Return-Path** → Actual sender path
- **Received** → Shows email routing path
- **Reply-To** → Where replies will go

## Investigation Summary
- Identified a phishing email impersonating a trusted service
- Detected mismatch between displayed URL and actual link
- Found suspicious sender domain not matching official domain
- Recognized social engineering tactics (urgency + fear)

## Tools Used
- Browser inspection (hover over links)
- Email header analyzer tools
- Manual inspection of email content

## Key Learning
Phishing attacks rely heavily on human behavior rather than technical vulnerabilities. Awareness and careful inspection are key to prevention.

## Screenshots

### Phishing Email Example
![Phishing Email](screenshots/phishing-email.png)

### Suspicious Link
![Suspicious Link](screenshots/suspicious-link.png)

### Email Header Analysis
![Header Analysis](screenshots/header-analysis.png)
