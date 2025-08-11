# Microsoft Defender TVM Remediation Case

## Overview
This project demonstrates how I used **Microsoft Defender for Endpoint Threat & Vulnerability Management (TVM)** to identify, remediate, and verify security vulnerabilities in a lab environment.  
The process was mapped against **ISO/IEC 27001:2022** Annex A controls to show alignment with security governance best practices.

## Objective
- Detect high-severity vulnerabilities.
- Remediate affected systems.
- Verify risk reduction.
- Map actions to ISO 27001 controls.

## Tools Used
- Microsoft Defender for Endpoint TVM
- Microsoft Endpoint Manager
- Windows 11 VM

## Method
1. **Identify vulnerabilities** from TVM dashboard (e.g., outdated 7-Zip, OpenSSL, Paint).
2. **Request remediation** via Endpoint Manager.
3. **Deploy updates** to affected VMs.
4. **Run antivirus scan** to confirm no residual threats.
5. **Verify updates** were successfully installed.

## Evidence
All screenshots of the process are in the `Evidence` folder.

## ISO 27001 Mapping
Full control mapping is in `ISO27001-Mapping.md`.

## Outcome
- All targeted vulnerabilities remediated.
- Devices brought into compliance.
- Demonstrated ability to manage vulnerabilities and align with ISO 27001 governance.

---
