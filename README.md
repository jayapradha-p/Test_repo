# GitSync

## Integrations
|Name|Description|
|----|-----------|
|Flashpoint|Flashpoint is a global trusted leader in risk intelligence for organizations. From bolstering cyber and physical security, to detecting fraud and insider threats. Flashpoint enables users to enrich and enhance their internal data with our targeted data acquired from highly-curated sources.|
|Forti Manager|FortiManager provides one console to manage your network, giving you full control of your Fortinet devices with enterprise-class management.|
|Fortinet FortiSIEM|FortiSIEM brings together visibility, correlation, automated response, and remediation in a single, scalable solution. It reduces the complexity of managing network and security operations to effectively free resources, improve breach detection, and even prevent breaches.|
|Functions|A set of math and data manipulation actions created for Google SecOps Community to power up playbook capabilities.|
|Google Chronicle|Google SecOps enables you to examine the aggregated security information for your enterprise going back for months or longer. Use Google SecOps to search across all of the domains accessed from within your enterprise. To enable the Google API client to communicate with the Backstory API you will need Google Developer Service Account Credential, https://developers.google.com/identity/protocols/OAuth2#serviceaccount.|
|Google SecOps AI Agents|This integration provides first-party AI agents for Google Chronicle. It allows users to leverage Google's advanced AI capabilities for security operations and threat intelligence within the Chronicle platform.|
|MSSQL|Microsoft SQL Server is a relational database management system developed by Microsoft.|
|McAfee TIE|McAfee Threat Intelligence Exchange optimizes threat detection and response by closing the gap from malware encounter to containment from days, weeks, and months down to milliseconds.|
|Microsoft Azure Sentinel|Microsoft Azure Sentinel is a scalable, cloud-native, security information event management (SIEM) and security orchestration automated response (SOAR) solution. Azure Sentinel delivers intelligent security analytics and threat intelligence across the enterprise, providing a single solution for alert detection, threat visibility, proactive hunting, and threat response.|
|Microsoft Graph Mail|Microsoft 365 and Office 365 deliver the power of cloud productivity to businesses of all sizes, helping save time, money, and free up valued resources. The Microsoft 365 and Office 365 plans combine the familiar Microsoft Office desktop suite with cloud-based versions of Microsoft's next-generation communications and collaboration services (including Office for the web, Microsoft Exchange Online, Microsoft Teams, and Microsoft SharePoint Online) to help users be productive from virtually anywhere through the Internet. This integration uses Microsoft Graph Mail API to communicate with Microsoft 365 and Office 365 services.|
|Microsoft Graph Mail Delegated|This integration version uses Delegated Authentication in Microsoft 365 and requires interactive login of the user on behalf of which integration should communicate with Microsoft 365. To configure this integration, provide all parameters except for Refresh Token, and save the integration configuration, then run “Get Authorization” and “Generate Token” actions to get the token and then provide it in integration configuration to finish the process. Microsoft 365 and Office 365 deliver the power of cloud productivity to businesses of all sizes, helping save time, money, and free up valued resources. The Microsoft 365 and Office 365 plans combine the familiar Microsoft Office desktop suite with cloud-based versions of Microsoft's next-generation communications and collaboration services (including Office for the web, Microsoft Exchange Online, Microsoft Teams, and Microsoft SharePoint Online) to help users be productive from virtually anywhere through the Internet. This integration uses Microsoft Graph Mail API to communicate with Microsoft 365 and Office 365 services.|
|Microsoft Teams|Microsoft Teams is a platform that combines workplace chat, meetings, notes, and attachmentsQuick Guide: you must first register your app at Microsoft App Registration Portal, Configure Microsoft Teams Integration, Run the action 'Get Authorization', Run the action 'Generate Token'.|
|MongoDB|MongoDB is a free and open-source cross-platform document-oriented database program.|


## Connectors
|Name|Description|Has Mappings|
|----|-----------|------------|
|Google Chronicle - Chronicle Alerts Connector|Pull information about Rule based alerts from Google Chronicle. Note: dynamic list is used for filtering purposes. For all of the details please visit the documentation portal.|True|
|Palo Alto Cortex XDR Connector|Pull incidents from Palo Alto XDR. Dynamic List works with the “source” parameter.|False|
|hello|Pull incidents from Palo Alto XDR. Dynamic List works with the “source” parameter.|False|


## Playbooks
|Name|Description|
|----|-----------|
|Azure AD Enrichment|This block enriches Siemplify Host and User entities with relevant information from Azure Active Directory, providing additional context to support investigation and response activities.|
|Clean Case|Clean case (Tags, Alert scoring info, etc) when playbooks that are often rerun and can create duplicate evidence.  Extend this logic to meet your requirements.|
|New Block|An embedded workflow that can receive inputs and return an output.|
|New Playbook||


## Jobs
|Name|Description|
|----|-----------|
|Google Chronicle Alerts Creator Job - 1|This job will sync new SOAR alerts with Chronicle SIEM.Note: This job is only supported from Chronicle SOAR version 6.2.30 and higher.|
|Google Chronicle Alerts Creator Job - 2|This job will sync new SOAR alerts with Chronicle SIEM.Note: This job is only supported from Chronicle SOAR version 6.2.30 and higher.|
|Google Chronicle Alerts Creator Job|This job will sync new SOAR alerts with Chronicle SIEM.Note: This job is only supported from Chronicle SOAR version 6.2.30 and higher.|
|Google Chronicle Sync Job|This job will synchronize information about Chronicle SOAR Cases and Chronicle SOAR Alerts with Chronicle SIEM. Note: This job is only supported from Chronicle SOAR version 6.1.44 and higher.|
|Sync Incidents|This job synchronizes Google SecOps Alerts and Palo Alto XDR Incidents. It ensures that comments and status are kept in sync between the two systems. For the job to identify the correct information, the Google SecOps case must have the "Palo Alto XDR Incident" tag. If the alert didn’t originate from "Palo Alto Cortex XDR Connector",  you will need to add an "Incident_ID" context value to the case for the job to be able to find the correct information.|

