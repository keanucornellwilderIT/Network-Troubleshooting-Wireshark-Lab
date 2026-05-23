# Network Troubleshooting & Wireshark Lab

## Project Overview

This project simulates real-world enterprise network troubleshooting scenarios using common networking tools and packet analysis techniques. The lab provides hands-on experience diagnosing DNS issues, DHCP problems, network connectivity failures, and analyzing traffic with Wireshark.

The environment includes:

- DNS troubleshooting
- DHCP troubleshooting
- Packet capture and analysis
- Network connectivity diagnostics
- Enterprise troubleshooting workflows

---

## Technologies Used

- Wireshark
- Windows Server 2022
- Windows 10/11
- DNS
- DHCP
- PowerShell
- Command Prompt (CMD)
- ICMP / TCP / UDP protocols

---

## Lab Architecture

| Component | Purpose |
|---|---|
| Domain Controller | DNS and DHCP services |
| Client-1 | Workstation for troubleshooting |
| Wireshark | Packet capture and analysis |
| Internal Network | Enterprise communication testing |

---

## Project Sections

- [DNS & DHCP Troubleshooting](#dns--dhcp-troubleshooting)
- [Wireshark Packet Analysis](#wireshark-packet-analysis)
- [Network Connectivity Troubleshooting](#network-connectivity-troubleshooting)

---

# DNS & DHCP Troubleshooting

## Objective
Diagnose and resolve DNS and DHCP-related network issues.

## Tasks Completed
- Verified DNS resolution
- Tested DHCP address assignment
- Renewed IP configurations
- Flushed DNS cache
- Diagnosed network communication failures

## Commands Used

```powershell
ipconfig /all
ipconfig /release
ipconfig /renew
ipconfig /flushdns
nslookup
ping
