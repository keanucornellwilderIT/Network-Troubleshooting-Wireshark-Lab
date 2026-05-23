# Network Troubleshooting & Wireshark Lab

Repository: `Network-Troubleshooting-Wireshark-Lab`

## 📌 Overview
This project simulates real-world network troubleshooting and help desk scenarios using Windows networking tools and Wireshark packet analysis. The lab focuses on diagnosing connectivity problems, DNS issues, DHCP configuration problems, and packet-level troubleshooting commonly encountered in IT support environments.

The goal of this project is to strengthen troubleshooting methodology, improve understanding of network communication, and gain hands-on experience analyzing traffic in enterprise-style environments.

---

## 🎯 Objectives
- Troubleshoot DNS resolution issues
- Analyze DHCP configurations and IP addressing
- Capture and inspect packets using Wireshark
- Test network connectivity using command-line tools
- Practice real-world help desk troubleshooting workflows
- Strengthen understanding of TCP/IP networking

---

## 🧰 Technologies Used
- Windows 10/11
- Wireshark
- Command Prompt
- TCP/IP Networking
- DNS
- DHCP
- Ping
- Tracert/Traceroute
- ipconfig
- nslookup

---

## 🏗️ Environment Setup

### Devices Used
- Windows Client Machine
- Home/Virtual Network Environment

### Network Configuration
- DHCP Enabled
- Private IPv4 Addressing
- DNS Resolution Testing
- Internet Connectivity Validation

---

## ⚙️ Project Configuration Steps

### Step 1 - Install Wireshark
- Downloaded and installed Wireshark
- Configured packet capture permissions
- Verified active network adapters

Screenshot here

---

### Step 2 - Verify Network Configuration
- Used `ipconfig /all`
- Reviewed IP address, subnet mask, gateway, and DNS server information
- Confirmed DHCP configuration

Screenshot here

---

### Step 3 - Perform Connectivity Testing
- Tested connectivity using `ping`
- Used `tracert` to analyze routing paths
- Verified internet communication

Screenshot here

---

### Step 4 - Capture Network Traffic
- Started packet captures in Wireshark
- Filtered traffic using protocols and IP addresses
- Analyzed DNS, ICMP, and TCP packets

Screenshot here

---

## 🛠️ Help Desk Scenarios

### Scenario 1 - DNS Troubleshooting

#### Problem
User could not access websites despite having internet connectivity.

#### Troubleshooting
- Ran `ping` tests
- Used `nslookup`
- Reviewed DNS server settings
- Tested hostname resolution

#### Root Cause
Incorrect or unreachable DNS server configuration.

#### Resolution
Updated DNS settings and confirmed successful name resolution.

#### Skills Learned
- DNS troubleshooting
- Name resolution diagnostics
- Network connectivity testing
- Command-line troubleshooting

Screenshot here

---

### Scenario 2 - DHCP Configuration Issue

#### Problem
Client device was unable to obtain a valid IP address.

#### Troubleshooting
- Ran `ipconfig /all`
- Checked DHCP lease information
- Renewed IP configuration using `ipconfig /renew`
- Verified network adapter settings

#### Root Cause
DHCP lease/configuration issue causing invalid network assignment.

#### Resolution
Renewed DHCP lease and restored proper network connectivity.

#### Skills Learned
- DHCP troubleshooting
- IP addressing concepts
- Network adapter diagnostics
- Windows networking support

Screenshot here

---

### Scenario 3 - Packet Capture Analysis

#### Problem
Need to identify network communication behavior and troubleshoot traffic flow.

#### Troubleshooting
- Captured packets using Wireshark
- Applied protocol filters
- Analyzed ICMP, DNS, and TCP traffic
- Reviewed packet timing and communication flow

#### Root Cause
Traffic analysis used to identify communication patterns and connectivity issues.

#### Resolution
Validated successful communication and identified network behavior through packet analysis.

#### Skills Learned
- Packet analysis
- Wireshark filtering
- TCP/IP troubleshooting
- Network traffic inspection

Screenshot here

---

### Scenario 4 - Ping & Traceroute Diagnostics

#### Problem
User experienced intermittent connectivity issues to external resources.

#### Troubleshooting
- Used `ping` for latency and packet loss testing
- Ran `tracert` to identify routing path
- Compared hop responses

#### Root Cause
Network path latency and routing inconsistencies.

#### Resolution
Validated route path and identified potential network bottlenecks.

#### Skills Learned
- ICMP diagnostics
- Traceroute analysis
- Connectivity troubleshooting
- Network path analysis

Screenshot here

---

### Scenario 5 - Connectivity Troubleshooting

#### Problem
User unable to connect to network resources.

#### Troubleshooting
- Verified physical and logical connectivity
- Tested local gateway communication
- Checked DNS and internet access
- Reviewed IP configuration

#### Root Cause
Network configuration/connectivity issue affecting communication.

#### Resolution
Corrected connectivity settings and restored access.

#### Skills Learned
- Network troubleshooting methodology
- Root cause analysis
- Windows networking
- Help desk troubleshooting workflows

Screenshot here

---

## 🧠 Key Help Desk Skills Demonstrated
- Troubleshooting methodology
- Root cause analysis
- Windows networking
- DNS troubleshooting
- DHCP troubleshooting
- Packet analysis
- Connectivity diagnostics
- Command-line networking tools
- Technical documentation

---

## 📖 Lessons Learned
This project improved my understanding of enterprise networking fundamentals and real-world troubleshooting processes. I learned how to diagnose connectivity issues systematically, analyze network traffic using Wireshark, and use networking utilities to identify root causes efficiently. The lab also strengthened my documentation and help desk troubleshooting skills.

---

## 🚀 Future Improvements
- Add VLAN troubleshooting scenarios
- Simulate enterprise firewall configurations
- Analyze HTTP/HTTPS traffic
- Add advanced Wireshark filtering
- Create Active Directory network scenarios
- Add VPN troubleshooting exercises

---

## 📸 Screenshots
Include:
- `ipconfig /all`
- Ping tests
- Traceroute results
- Wireshark packet captures
- DNS lookup results
- DHCP lease information
- Connectivity troubleshooting screenshots

---

## 👨‍💻 Author
Keanu

LinkedIn: YOUR_LINKEDIN_HERE

GitHub: YOUR_GITHUB_HERE
