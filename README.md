# Wireshark & Network Troubleshooting Help Desk Lab

## Overview
This project demonstrates basic help desk and network troubleshooting scenarios using Wireshark within a Windows domain environment. The lab focuses on DNS troubleshooting, shared drive connectivity issues, and network communication testing commonly handled by IT support technicians.

---

## Business Impact
Network and connectivity issues can prevent users from accessing internal systems, shared drives, and company resources, impacting daily business operations.

---

## Technologies Used
- Wireshark
- Windows Server 2022
- Windows 10 Enterprise
- Active Directory
- DNS
- SMB/File Sharing
- Microsoft Azure

---

## Environment Setup
- Azure Virtual Machines
- Domain Controller (dc-1)
- Client Machine (client-1)
- Active Directory Domain Environment
- Finance Shared Drive

---

## Skills Demonstrated
- DNS Troubleshooting
- Shared Drive Troubleshooting
- Wireshark Packet Analysis
- Connectivity Testing
- Network Diagnostics
- Help Desk Troubleshooting

---

# Scenarios

---

# Scenario 1 - DNS Troubleshooting

### Problem
Users were unable to access internal resources due to DNS resolution issues within the environment.

### Troubleshooting
- Tested hostname resolution using ping and nslookup
- Reviewed DNS configuration
- Captured DNS traffic using Wireshark
- Corrected DNS settings and verified communication

## Screenshots

### Failed DNS resolution using ping or nslookup  

<img width="976" height="510" alt="image" src="https://github.com/user-attachments/assets/d5d75810-cc5d-41ed-95b8-4a7bdf1d8295" />

### Wireshark DNS packet capture

<img width="1918" height="1040" alt="image" src="https://github.com/user-attachments/assets/ac9fdc08-f878-43a9-87e0-ae748c2e4c23" />

### DNS configuration investigation 

<img width="788" height="69" alt="image" src="https://github.com/user-attachments/assets/9ae76c2d-6954-4932-a69f-3cd9e848e53e" />

### Restored successful hostname resolution  
<img width="590" height="476" alt="image" src="https://github.com/user-attachments/assets/537ab535-d1e1-436b-9679-7e58d3bbc9de" />

### Resolution
Corrected DNS configuration and restored successful communication with internal resources.

---

# Scenario 2 - Finance Shared Drive Connectivity Failure

### Problem
Finance users were unable to access a shared network drive containing department files and reports.

### Troubleshooting
- Tested connectivity to dc-1
- Investigated Finance shared folder configuration
- Captured SMB traffic using Wireshark
- Restored shared folder access

## Screenshots

### Failed access to `\\dc-1\Finance`  

<img width="1114" height="627" alt="image" src="https://github.com/user-attachments/assets/3e9272c9-1285-49da-9d8a-02d9c5a87d55" />

### Successful ping to dc-1 during investigation  

<img width="659" height="374" alt="image" src="https://github.com/user-attachments/assets/c3028f79-64b4-4ea6-8568-053201253f71" />

### Shared folder configuration review 

<img width="358" height="478" alt="image" src="https://github.com/user-attachments/assets/85112e8f-c96c-4cbc-ab13-1c24fd0765f8" />

### Wireshark SMB traffic capture  

<img width="1920" height="708" alt="image" src="https://github.com/user-attachments/assets/c4006ea3-2462-44b6-914f-b90397132e3b" />

### Restored shared drive access  

<img width="1118" height="644" alt="image" src="https://github.com/user-attachments/assets/defea5dc-75ce-4b70-9a33-81dcec79197a" />

### Resolution
Re-enabled shared folder access and verified successful connectivity to the Finance shared drive.

---

# Scenario 3 - Connectivity Investigation

### Problem
Users experienced intermittent network communication issues between systems within the environment.

### Troubleshooting
- Performed ping diagnostics
- Ran tracert testing
- Captured ICMP traffic using Wireshark
- Verified successful communication between systems

## Screenshots

### Ping connectivity testing

<img width="585" height="353" alt="image" src="https://github.com/user-attachments/assets/e7402035-3196-4774-b260-03d27d21900d" />

### Tracert investigation 

<img width="617" height="233" alt="image" src="https://github.com/user-attachments/assets/3d9bb839-e76d-4ff1-8ef0-e2d3f4d34d70" />

### Wireshark ICMP packet capture  

<img width="1798" height="778" alt="image" src="https://github.com/user-attachments/assets/63a43f50-0c66-480c-a4ec-7900f909e9fb" />
  
### Resolution
Verified successful communication between systems and confirmed stable network connectivity.

---

## Lessons Learned
This project improved my understanding of Wireshark, DNS troubleshooting, SMB traffic analysis, and network diagnostics within a Windows domain environment. I gained hands-on experience using packet captures to support help desk troubleshooting scenarios and investigate real network communication issues.

