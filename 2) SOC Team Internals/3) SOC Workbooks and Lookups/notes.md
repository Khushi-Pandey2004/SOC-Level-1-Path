#Identity Inventory
Identity inventory is a catalogue of corporate employees (user accounts), services (machine accounts), and their details like privileges, contacts, and roles within the company. 

#Sources of Identities:

##Active Directory:
Eg: On-prem AD, Entra ID
AD itself is an identity database, and it is commonly used by SOC.

##SSO Providers:
Eg: Okta, Google Workspace
Cloud alternative for AD, an easy way to manage and search the users

##HR Systems:
Eg: BambooHR, SAP, HiBob
Limited to employees only, but usually provides full employee data

##Custom Solution:
Eg: CSV or Excel Sheets
It is common for IT or security teams to maintain their own solutions

#Asset Inventory
Asset inventory, also called asset(software, hardware, or employees) lookup, is a list of all computing resources within an organisation's IT environment. 

#Sources of Assets:

##Active Directory
same as in source of identities.

##SIEM or EDR:
Eg: Elastic, CrowdStrike
Some SIEM or EDR agents collect information about the monitored hosts

##MDM Solution:
Eg: MS Intune, Jamf MDM
A dedicated class of solutions created to list and manage assets

##Custom Solution:
same as in source of identities.

#EDR
Endpoint detection and response (EDR) is a series of tools that monitor devices for activity that could indicate a threat.

#SIEM
Security Information and Event Management system that is used to aggregate security information in the form of logs, alerts, artifacts and events into a centralized platform that would allow security analysts to perform near real-time analysis during security monitoring.

#AD
Active Directory is a directory service developed by Microsoft for Windows domain networks. It stores information about network objects such as computers, users, and groups. It provides authentication and authorisation services, and allows administrators to manage network resources centrally.

#SOAR
SOAR stands for Security Orchestration, Automation, and Response. It is a solution that helps organisations to streamline and automate their security operations, including incident management, threat intelligence, and vulnerability response.

#Network Diagrams
A network diagram, a visual schema presenting existing locations, subnets, and their connections.

#SOC Workbooks
SOC workbook, also called playbook, runbook, or workflow, is a structured document that defines the steps required to investigate and remediate specific threats efficiently and consistently.


##Enrichment: 
Use Threat Intelligence and identity inventory to get information about the affected user

##Investigation:
Using the gathered data and SIEM logs, make your verdict if the login is expected

##Escalation:
Escalate the alert to L2 or communicate the login with the user if necessary

