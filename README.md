Home SOC Lab
Overview

This project documents the creation of a Security Operations Center (SOC) lab designed to simulate an enterprise monitoring environment. The lab collects and centralizes security logs from Windows and Linux endpoints into Splunk Enterprise, providing a foundation for security monitoring, threat detection, and incident investigation.


Objectives
Deploy a functional SIEM environment using Splunk Enterprise
Centralize Windows and Linux security logs
Collect enhanced endpoint telemetry using Sysmon
Configure log forwarding with Splunk Universal Forwarder
Build a foundation for detection engineering and threat hunting
Lab Architecture
+----------------------+          +----------------------+
|   Windows Endpoint   |          |    Linux Endpoint    |
|   Sysmon             |          |    rsyslog           |
+----------+-----------+          +----------+-----------+
           |                                 |
    Splunk Universal Forwarder        Splunk Universal Forwarder
           |                                 |
           +---------------------------------+
                              |
                              v
                   +----------------------+
                   |   Splunk Enterprise  |
                   |      SIEM Server     |
                   +----------------------+
Technologies Used
Splunk Universal Forwarder
Splunk Enterprise
Sysmon
Ubuntu Server
Windows 10
VirtualBox
Ubuntu Linux
PowerShell
Roadmap
Phase 1 - Completed
Infrastructure deployment ✅
Log collection ✅
Endpoint telemetry ✅
Phase 2
Brute-force detection
PowerShell monitoring
Process creation analysis
Network connection monitoring
Detection engineering
Alert creation
Phase 3
Threat hunting
Dashboards
MITRE ATT&CK mapping
Incident investigations
Skills Demonstrated
SIEM Administration
Windows Event Logging
Linux Log Management
Endpoint Telemetry
Splunk Universal Forwarder Configuration
Virtual Network Configuration
Log Ingestion Validation
