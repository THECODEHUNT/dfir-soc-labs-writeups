# Wireshark Traffic Analysis

## Objective
Analyze network traffic using Wireshark to identify suspicious activity and understand packet-level communication.

## Tools Used
- Wireshark

## Key Concepts Covered
- Packet capture analysis
- Protocol identification (HTTP, DNS, TCP)
- Filtering traffic
- Identifying suspicious patterns

---

## Steps Performed

### 1. Capturing Traffic
- Opened Wireshark
- Selected active network interface
- Started packet capture

### 2. Applying Filters
Used filters to analyze specific traffic:

```bash
http
dns
tcp.port == 80
ip.addr == 192.168.1.1
```
### 3. Protocol Analysis
Identified HTTP requests and responses
Observed DNS queries and domain resolutions
Analyzed TCP handshake (SYN, ACK)

### 4. Suspicious Indicators
Unusual DNS queries
Repeated requests to unknown IPs
Cleartext credentials in HTTP (if present)

### Findings
Observed normal web traffic (HTTP)
DNS queries resolving domain names
TCP connections established successfully
Learned how attackers can hide data in normal traffic

### Key Learning

Wireshark helps in deep packet inspection and is essential for DFIR investigations.
It allows analysts to detect anomalies, suspicious communication, and potential data exfiltration.

## Screenshots

### Packet Capture
![Capture](screenshots/capture.png)

### HTTP Traffic
![HTTP](screenshots/http.png)

### DNS Queries
![DNS](screenshots/dns.png)
