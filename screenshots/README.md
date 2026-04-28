# Screenshots – Active Directory Security Lab

This folder contains visual evidence from a cybersecurity lab simulating Active Directory attack and detection scenarios using Kali Linux and Windows Server.

Each screenshot represents a key stage of the attack lifecycle: reconnaissance, exploitation, and detection.

---

## Lab Setup
- Virtual machines: Domain Controller, CLIENT1, Kali Linux
- Virtualization: VirtualBox
- Network: Internal isolated lab environment

---

## Screenshot Breakdown

### 01 – Virtual Machine Setup
Shows all three virtual machines running (DC, CLIENT1, Kali Linux).

---

### 02 – Network Configuration
Displays IP configuration confirming all machines are on the same internal network.

---

### 03 – Nmap Reconnaissance
Output of network scan identifying open Active Directory services such as Kerberos, LDAP, and SMB.

---

### 04 – SMB Anonymous Access
Evidence of successful anonymous SMB connection using Kali Linux.

---

### 05 – Authentication Failure Logs (Event ID 4625)
Windows Security Event Viewer showing failed login attempts generated during the attack simulation.

---

### 06 – Source IP Attribution
Highlights attacker source IP address identified in Windows logs, linking activity back to Kali Linux.

---

## Purpose of These Screenshots
These images demonstrate:
- Network reconnaissance techniques
- Authentication attack simulation
- Security log generation and analysis
- Detection of suspicious login activity in an Active Directory environment

---

## Notes
All activity was performed in a controlled lab environment for educational and educational cybersecurity practice purposes only.
