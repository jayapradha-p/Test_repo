# GitSync

## Connectors
|Name|Description|Has Mappings|
|----|-----------|------------|
|Azure Security Center - Security Alerts Connector|Pull security alerts from Azure Security Center. Note: whitelist works with alertType field.|False|
|Azure Security Center - hello connector - new|Pull security alerts from Azure Security Center. Note: whitelist works with alertType field.|False|


## Playbooks
|Name|Description|
|----|-----------|
|New Playbook|This is TestingTesting purposehello this is testinghello|
|playbook-5-2026|HellothisisTesting|


## Jobs
|Name|Description|
|----|-----------|
|projects/project/locations/location/instances/instance/integrations/GoogleChronicle/jobs/2/jobInstances/8|This job will sync new SOAR alerts with Chronicle SIEM.Note: This job is only supported from Chronicle SOAR version 6.2.30 and higher.|
|projects/project/locations/location/instances/instance/integrations/PaloAltoCortexXDR/jobs/42/jobInstances/9|This job synchronizes Google SecOps Alerts and Palo Alto XDR Incidents. It ensures that comments and status are kept in sync between the two systems. For the job to identify the correct information, the Google SecOps case must have the "Palo Alto XDR Incident" tag. If the alert didn’t originate from "Palo Alto Cortex XDR Connector",  you will need to add an "Incident_ID" context value to the case for the job to be able to find the correct information.|

