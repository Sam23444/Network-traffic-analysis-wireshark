# Network Traffic Analysis Using Wireshark

## Objective
Analyze network traffic and identify security-relevant activity using Wireshark.

## Tools Used
- Wireshark
- Windows 11
- Command Prompt

## Traffic Types Investigated
- HTTP
- HTTPS/TLS
- DNS
- ICMP

## Key Findings

### HTTP Analysis
Observed plaintext web traffic including GET requests and host headers.

### HTTPS Analysis
TLS encryption protected payload visibility.

### DNS Analysis
Captured DNS queries resolving domains to IP addresses.

### ICMP Analysis
Observed echo request/reply communication.

## Suspicious Activity Checks
- SYN traffic analysis
- Retransmission analysis
- Port investigation

## Security Recommendations
- Use HTTPS instead of HTTP
- Monitor unusual ports
- Inspect excessive SYN traffic