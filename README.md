# 🔐 LockBit Ransomware Analysis – Citrix Bleed Exploitation

## 📌 Overview
This project presents a detailed threat intelligence and incident response analysis of the October 2023 LockBit ransomware attack targeting Boeing. The attackers exploited CVE-2023-4966 (Citrix Bleed) to hijack NetScaler session tokens, bypass authentication, deploy persistence mechanisms, and exfiltrate approximately 40GB of sensitive data.

This case study examines the full attack lifecycle, maps adversary behavior to the MITRE ATT&CK framework, and proposes defensive controls aligned with CISA and CIS guidelines.

## 🧠 Key Areas Covered
- Initial Access via CVE-2023-4966
- Session hijacking and MFA bypass
- Lateral movement tools (PsExec, Mimikatz, AnyDesk)
- Data exfiltration (40GB)
- MITRE ATT&CK technique mapping
- Kill Chain defensive matrix
- CIS and CISA control alignment

## 🔎 SOC-Relevant Skills Demonstrated
- Threat intelligence analysis
- IOC identification
- MITRE ATT&CK mapping
- Ransomware investigation
- Defensive control recommendations
