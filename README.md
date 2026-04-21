# Active Directory Detection Validation with Splunk and Atomic Red Team

![Splunk](https://img.shields.io/badge/SIEM-Splunk-black?logo=splunk)
![Atomic Red Team](https://img.shields.io/badge/Adversary_Emulation-Atomic_Red_Team-red)
![MITRE ATT&CK](https://img.shields.io/badge/Framework-MITRE_ATT%26CK-critical)
![PowerShell](https://img.shields.io/badge/Scripting-PowerShell-5391FE?logo=powershell)
![VirtualBox](https://img.shields.io/badge/Lab-VirtualBox-183A61?logo=virtualbox)
![Windows 10](https://img.shields.io/badge/OS-Windows_10-0078D6?logo=windows)
![Windows Server 2022](https://img.shields.io/badge/OS-Windows_Server_2022-0078D6?logo=windows)
![Ubuntu Server 22.04](https://img.shields.io/badge/OS-Ubuntu_22.04-E95420?logo=ubuntu)

## Overview

This project demonstrates a detection engineering homelab where **Atomic Red Team** was used to simulate adversary behavior and generate **PowerShell-related telemetry** in a Windows-based Active Directory lab. The resulting activity was reviewed in **Splunk** to validate visibility, improve understanding of event generation, and strengthen detection-focused analysis.

Instead of only describing tool usage, this project highlights the workflow of:

- building a multi-system lab
- emulating attacker behavior with Atomic Red Team
- mapping activity to **MITRE ATT&CK**
- reviewing the resulting telemetry in **Splunk**
- validating that the lab can surface meaningful security events

## Why This Project Matters

This lab demonstrates skills relevant to blue team, SOC, and detection engineering roles:

- adversary emulation in a controlled lab
- MITRE ATT&CK technique mapping
- PowerShell activity generation and review
- SIEM analysis in Splunk
- Windows and Active Directory lab familiarity
- security documentation and technical reporting

## Lab Environment

### Tools

- Splunk
- Atomic Red Team
- MITRE ATT&CK
- PowerShell

### Systems

- VirtualBox
- Windows 10
- Windows Server 2022
- Ubuntu Server 22.04
- Kali Linux

## Detection Focus

This project focused on using **Atomic Red Team** to invoke a PowerShell-based test aligned to:

- **MITRE ATT&CK T1059.001 – PowerShell**

The objective was to generate realistic telemetry in the lab and verify that the activity could be identified in Splunk.

## Project Workflow

1. Build a multi-VM lab with Windows and supporting infrastructure
2. Review relevant MITRE ATT&CK techniques
3. Use Atomic Red Team to execute a PowerShell-based test
4. Generate security-relevant activity on the target host
5. Review resulting events and telemetry in Splunk
6. Document the findings and detection value of the test

## Skills Demonstrated

| Area | Demonstrated Skill |
|---|---|
| SIEM Analysis | Investigated PowerShell-related telemetry in Splunk |
| Detection Engineering | Validated visibility from simulated adversary behavior |
| Adversary Emulation | Executed Atomic Red Team test cases in a controlled lab |
| Threat Mapping | Connected test activity to MITRE ATT&CK T1059.001 |
| Windows Security | Worked with PowerShell-generated security activity |
| Lab Engineering | Built and tested a multi-machine virtualized environment |

## Screenshots

### Network Diagram

![Network Diagram](images/network-diagram.png)

### MITRE ATT&CK Technique Reference

![MITRE ATT&CK Mapping](images/mitre-attack-mapping.png)

### Atomic Red Team Setup / Technique Review

![Atomic Red Team Overview](images/atomic-red-team-overview.png)

### Invoking Atomic Test T1059.001

![Invoke Atomic T1059.001](images/invoke-atomic-t1059-001.png)

### Splunk Detection View

![Splunk PowerShell Detection](images/splunk-powershell-detection.png)

## Key Takeaways

- Atomic Red Team is effective for generating realistic test activity in a homelab
- MITRE ATT&CK mapping helps tie lab exercises to real-world adversary behaviors
- Splunk can be used to validate whether important PowerShell activity is visible and reviewable
- Detection-focused labs are a strong way to build blue-team and SOC-ready experience

## Future Improvements

- Add Splunk search queries or detection logic used during analysis
- Expand testing to additional ATT&CK techniques
- Include Sysmon or Windows event logging enhancements
- Document false positives and tuning opportunities
- Add a dedicated detection engineering notes section

## About This Repository

This repository is part of my cybersecurity homelab work focused on:

- SIEM analysis
- adversary emulation
- Active Directory security
- detection validation
- defensive skill building
