# Windows Threat Detection & Incident Response Lab

## Overview

This project is a Windows security monitoring lab built to practice log collection, threat detection, incident investigation, and security event analysis.

The lab uses Splunk, Sysmon, Windows Event Logs, and PowerShell to collect and investigate authentication, process, and account activity in a controlled virtual environment.

This project is currently in progress and will be updated as detections and investigation scenarios are completed.

## Technologies

- Splunk
- Sysmon
- Windows Event Logs
- PowerShell
- Windows 11
- VirtualBox
- MITRE ATT&CK

## Planned Security Scenarios

### Failed Authentication Detection

Generate controlled failed logon attempts and use Windows authentication events in Splunk to identify repeated login failures and investigate the affected account and workstation.

### PowerShell Activity Detection

Generate safe PowerShell activity and use Sysmon process telemetry to identify PowerShell execution and analyze related process information.

### Account and Privilege Changes

Generate controlled account or security-group changes and use Windows security events to investigate who made the change, which account was affected, and when the activity occurred.

## Incident Investigation

Security events generated during the lab will be investigated by correlating Windows Event Logs and Sysmon telemetry in Splunk.

Relevant activity will also be mapped to MITRE ATT&CK techniques where applicable.

## Screenshots

Screenshots and investigation evidence will be added as each scenario is completed.

## Skills Practiced

- Security Monitoring
- Log Analysis
- Windows Event Logs
- Splunk
- Sysmon
- PowerShell
- Authentication Analysis
- Incident Response
- Event Correlation
- MITRE ATT&CK
