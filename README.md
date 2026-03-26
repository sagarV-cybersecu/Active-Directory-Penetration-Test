# 🔴 Active Directory Penetration Testing – Domain Compromise

## 📌 Overview
This project demonstrates a full internal Active Directory penetration testing engagement conducted in a controlled lab environment.

The objective was to identify vulnerabilities, exploit misconfigurations, and achieve Domain Administrator access.

---

## ⚔️ Attack Chain

- Reconnaissance & Enumeration (Nmap, LDAP)
- NTLM Relay Attack (LDAPS)
- Resource-Based Constrained Delegation (RBCD)
- Kerberoasting Attack
- gMSA Credential Extraction
- Privilege Escalation
- Lateral Movement
- Domain Controller Compromise

---

## 🛠️ Tools Used

- Nmap
- Impacket (ntlmrelayx, secretsdump, getST)
- Evil-WinRM
- DFSCoerce
- BloodHound
- Hashcat

---

## 🎯 Key Achievements

- Successfully exploited NTLM relay to modify AD permissions
- Abused RBCD for privilege escalation
- Extracted sensitive gMSA credentials
- Achieved full Domain Administrator access

---

## 📄 Report

Full detailed penetration testing report is available in the /report directory.

---

## ⚠️ Disclaimer

This project was conducted in a controlled lab environment for educational purposes only.
