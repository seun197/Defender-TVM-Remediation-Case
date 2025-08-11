
# 7-Zip Remediation

## Overview
This case documents the process of identifying, remediating, and verifying an outdated 7-Zip installation using Microsoft Defender for Endpoint Threat & Vulnerability Management (TVM).  
The workflow is mapped to ISO/IEC 27001:2022 Annex A controls for governance alignment.

## Objective
- Detect high-severity vulnerability in 7-Zip.
- Request remediation via Microsoft Endpoint Manager.
- Deploy the updated 7-Zip version.
- Verify installation and confirm no residual threats.
- Map remediation actions to ISO 27001 controls.

## Tools Used
- Microsoft Defender for Endpoint TVM
- Microsoft Endpoint Manager
- Windows 11 VM
- Windows Security Antivirus

## Method
1. **Identify Vulnerability**  
   Detected outdated 7-Zip via Microsoft Defender TVM dashboard.

2. **Request Remediation**  
   Submitted remediation request to update 7-Zip through Endpoint Manager.

3. **Deploy Update**  
   Installed latest 7-Zip version on the affected VM.

4. **Run Antivirus Scan**  
   Executed a full antivirus scan to ensure no malicious remnants.

5. **Verify Update**  
   Confirmed that the latest version of 7-Zip was installed.

## Evidence
Screenshots of each step are stored in the `Evidence` folder:  
- `01-Security Recommendations.png`
- `02-Request Remediation 7 Zip.png`
- `03-Remediation Request 7 Zip.png`
- `04-Install 7 Zip Update on VM.png`
- `05-Verify Latest 7-Zip Downloaded.png`
- `06-Run Antivirus for 7-Zip VM.png`

## ISO 27001 Mapping
See `ISO27001-Mapping.md` for the full control mapping.

## Outcome
- Vulnerability fully remediated.
- Device brought into compliance.
- Demonstrated structured remediation process aligned with ISO 27001 controls.
