# Network Troubleshooting & Wireshark Lab

## Overview
This project simulates real-world network troubleshooting scenarios within a Windows domain environment using networking tools and Wireshark packet analysis. The lab focuses on diagnosing DNS and connectivity issues, analyzing packet traffic, troubleshooting shared drive access, and testing communication between systems commonly managed by IT support specialists and network administrators.

The goal of this project is to build hands-on experience with enterprise networking, packet analysis, troubleshooting methodology, and real-world network diagnostics workflows.

## Business Impact
Network communication issues can prevent users from accessing domain resources, shared drives, printers, and internal systems, directly impacting business operations and employee productivity.

## Objectives
- Troubleshoot DNS connectivity issues
- Configure and verify DHCP settings
- Analyze network traffic using Wireshark
- Test communication using ping and tracert
- Troubleshoot shared drive connectivity
- Practice enterprise network troubleshooting workflows

## Technologies Used
- Wireshark
- Windows Server 2022
- Windows 10/11
- Active Directory Domain Services (AD DS)
- DNS
- DHCP
- Command Prompt
- File & Storage Services

## Environment Setup
- Azure Virtual Machines
- Windows Server VM (dc-1)
- Windows Client VM (client-1)
- Active Directory Domain Environment
- DNS & DHCP Services
- Finance Shared Drive
- Domain Users & Security Groups

## Key Help Desk Skills Demonstrated
- DNS Troubleshooting
- Network Diagnostics
- Packet Analysis
- Connectivity Troubleshooting
- Shared Drive Troubleshooting
- Root Cause Analysis

# Project Configuration Steps

### Step 1 - Configure Active Directory & Networking Services
Configured Active Directory, DNS, DHCP, File Services, and networking roles on the domain controller.

### Step 2 - Configure Finance Shared Drive
Created Finance OU, Finance security group, and configured shared folder permissions for department access.

### Step 3 - Verify Network Connectivity
Verified communication between dc-1 and client-1 using hostname resolution and ping testing.

### Step 4 - Capture Network Traffic Using Wireshark
Captured DNS and ICMP traffic using Wireshark packet analysis during troubleshooting scenarios.

---

# 🛠️ Help Desk Scenarios

# Scenario 1 - DNS Troubleshooting & Name Resolution Failure

### Problem
Users were unable to access internal domain resources because hostnames were failing to resolve properly within the network environment.

### Troubleshooting
- Verified baseline connectivity
- Reviewed DNS configuration
- Ran ipconfig /all diagnostics
- Tested hostname resolution using ping and nslookup
- Captured DNS traffic using Wireshark

### Root Cause
Incorrect DNS server configuration prevented successful hostname resolution and communication with internal domain resources.

### Screenshots
Successful ping to dc-1 before DNS failure
<img width="1024" height="617" alt="image" src="https://github.com/user-attachments/assets/7cc0d517-f502-4d50-9ac7-73e4bce4768d" />

Failed ping and nslookup after incorrect DNS configuration
<img width="1026" height="313" alt="image" src="https://github.com/user-attachments/assets/5b321964-e5e5-47f2-a0ad-e8a328f854a4" />

Wireshark DNS packet capture showing failed DNS queries
<img width="1917" height="708" alt="image" src="https://github.com/user-attachments/assets/845fe233-9a9b-45a6-ae67-cb766f68ec6e" />

ipconfig /all output showing incorrect DNS server
<img width="1136" height="73" alt="image" src="https://github.com/user-attachments/assets/c390efaa-63cd-4619-9dc3-bf135f13ae7b" />

Restored successful hostname resolution after correcting DNS settings
<img width="396" height="455" alt="image" src="https://github.com/user-attachments/assets/d98b69c5-1225-43f2-b195-49b8d0492c06" />
<img width="1919" height="772" alt="image" src="https://github.com/user-attachments/assets/803168d5-9f42-4e80-8878-d9fa9f5afff1" />

### Resolution
Corrected DNS server configuration, flushed DNS cache, and restored successful communication with internal domain resources.

---

# Scenario 2 - DHCP & Network Configuration Troubleshooting

### Problem
Client system experienced network communication failures after an incorrect static IP configuration was applied, preventing communication with internal domain resources.

### Troubleshooting
- Reviewed client IPv4 configuration
- Verified DNS settings
- Ran ipconfig /release and ipconfig /renew
- Tested client connectivity
- Reviewed assigned IP configuration using ipconfig /all
- Tested DNS communication using nslookup and ping

### Root Cause
An incorrect static IP configuration and invalid DNS settings prevented the client workstation from communicating with the internal domain environment.

## Screenshots

### Incorrect Static IP Configuration
This screenshot shows the client workstation configured with an incorrect static IPv4 address and invalid network settings during the simulated network communication failure scenario.

### Failed Network Communication
This screenshot shows failed communication attempts between `client-1` and internal domain resources during the troubleshooting investigation.

### Network Configuration Review Using ipconfig /all
This screenshot shows the output of `ipconfig /all` used to review the assigned IPv4 configuration, DNS settings, and gateway information on `client-1`.

### DNS Troubleshooting Commands
This screenshot shows DNS and connectivity troubleshooting commands used during the investigation process.

### Restored Automatic Network Configuration
This screenshot shows the client workstation restored to automatic IP and DNS configuration settings after troubleshooting the network communication issue.

### Successful Network Communication After Resolution
This screenshot shows successful internal communication and valid network configuration after restoring proper client network settings and renewing the client IP configuration.

### Resolution
Restored automatic IP addressing and DNS configuration settings, successfully re-establishing internal network communication and domain connectivity for the client workstation.

---

# Scenario 3 - Finance Shared Drive Connectivity Failure

### Problem
Finance employees lost access to a shared network drive containing department financial reports and spreadsheets.

### Troubleshooting
- Verified issue across multiple users
- Tested network connectivity
- Reviewed shared folder permissions
- Verified Finance security group access
- Tested shared drive communication

### Root Cause
Network connectivity disruption prevented users from accessing the Finance shared drive successfully.

### Screenshots
- Critical shared drive outage showing business impact
- Finance security group and shared folder permissions
- Failed shared drive access or network path error
- Network troubleshooting and connectivity testing
- Restored shared drive access verification

### Resolution
Restored network connectivity and verified successful access to Finance shared resources for affected users.

---

# Scenario 4 - Ping & Traceroute Connectivity Diagnostics

### Problem
Users experienced intermittent communication issues between network systems and internal resources.

### Troubleshooting
- Performed ping diagnostics
- Ran tracert testing
- Verified network paths
- Tested communication between systems
- Analyzed connectivity responses

### Root Cause
Network communication issue affected connectivity between client and server systems.

### Screenshots
- Ping testing between client-1 and dc-1
- tracert diagnostics output
- Connectivity testing results
- Packet responses shown in Command Prompt
- Restored successful communication testing

### Resolution
Verified successful communication paths and restored stable network connectivity between systems.

---

# Scenario 5 - Wireshark Packet Analysis

### Problem
Network communication issues required packet-level analysis to investigate DNS and connectivity behavior within the environment.

### Troubleshooting
- Captured network traffic using Wireshark
- Applied DNS and ICMP filters
- Reviewed packet communication flow
- Verified DNS query responses
- Analyzed network communication behavior

### Root Cause
Packet-level analysis was required to verify network communication and troubleshoot DNS-related traffic issues.

### Screenshots
- Wireshark DNS packet capture
- ICMP packet analysis
- Applied Wireshark filtering
- DNS query and response traffic
- Successful packet communication verification

### Resolution
Used Wireshark packet analysis to identify and verify successful network communication behavior and troubleshooting results.

## Lessons Learned
This project improved my understanding of enterprise networking, DNS troubleshooting, packet analysis, and connectivity diagnostics within Windows environments. I gained hands-on experience diagnosing DNS and DHCP issues, troubleshooting shared drive access, analyzing packet traffic with Wireshark, and verifying communication between systems using enterprise networking tools.

The lab also strengthened my troubleshooting methodology, networking knowledge, and technical documentation skills.

## Future Improvements
- Configure advanced Wireshark filtering
- Simulate firewall troubleshooting scenarios
- Implement VLAN/network segmentation testing
- Add VPN connectivity troubleshooting
- Configure network monitoring tools
