## Wireshark ICMP Traffic Analysis

### Overview
This project demonstrates analysis of ICMP Echo Request and Echo Reply packets using Wireshark.

### What was done
- Generated ICMP traffic using the `ping` command
- Captured packets with Wireshark
- Filtered ICMP traffic
- Analyzed packet structure across layers:
  - Ethernet (MAC addresses)
  - IP (source/destination addressing, TTL)
  - ICMP (type, code, sequence, checksum)

### Tools
- Wireshark
- Linux terminal (ping)

### Outcome
Improved understanding of ICMP behavior and packet flow between host and destination.
