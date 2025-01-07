# SOC-Automation-Lab

## Overview

This project demonstrates a fully functional Security Operations Center (SOC) automation lab using open-source tools to streamline incident response and case management. The lab integrates Wazuh, Shuffle, and The Hive to detect and respond to security threats in real time.

### Objectives

-	Generate and analyze security alerts from endpoint activity.
-	Automate incident response workflows using Shuffle.
-	Manage incidents effectively through The Hive.
-	Perform real-time reputation checks with VirusTotal.
-	Implement defensive actions, such as blocking malicious IP addresses.


## Architecture

The lab architecture includes:
1.	Wazuh: Deployed to monitor endpoint activity and generate alerts.
2.	Shuffle: Configured for automation workflows and integration between components.
3.	The Hive: Set up for case management and detailed incident tracking.

![image](https://github.com/user-attachments/assets/2717896a-7eb8-45f5-99a1-4a8fe4e72da2)

*Ref 1: Architecture Diagram*

### Setup Details
-	Wazuh was deployed on a cloud server to monitor activity from endpoint devices.
-	Shuffle was installed on a separate cloud server for orchestration and automation.
-	The Hive was hosted on another cloud server for case management and collaboration.
-	The monitored endpoint: Windows machine (DESKTOP-8AAR6BV (002)).

## Workflow
1.	Threat Generation and Detection:
-	A Mimikatz alert was triggered on the Windows endpoint (DESKTOP-8AAR6BV (002)).
-	Wazuh detected the alert and generated detailed logs, including a SHA256 hash of the suspected malware.
![image](https://github.com/user-attachments/assets/06f8e34c-5492-4917-b23f-11663a3f04b6)

*Ref 2: Mimikatz File executed on Windows client Machine*

![image](https://github.com/user-attachments/assets/75b16c47-8d81-493b-9a84-44e82fc451a2)

*Ref 3a: Mimikatz alert detected on Wazuh*

![image](https://github.com/user-attachments/assets/c7ad6e4e-b4ed-4d92-85ec-dbfef825ffbe)

*Ref 3b: Mimikatz alert detected on Wazuh*





Every screenshot should have some text explaining what the screenshot is about.

Example below.

*Ref 1: Network Diagram*
