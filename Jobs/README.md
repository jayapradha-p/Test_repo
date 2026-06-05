## CA Close Ticket In CA For Closed Case - 3
Sync closure of the tickets at the CA Desk Manager with Siemplify cases closure.


**Run Interval In Seconds:** 60

#### Parameters
|Name|Type|Is Mandatory|Value|
|----|----|------------|-----|
|API Root|String|True|http://x.x.x.x:<port>|
|Username|String|True|dsdsdsds|
|Password|String|True|sddssds|
|Group Filter|String||Test|
|Group Field|String|True|group.combo_name|
|Ticket Final Status|String|True|Closed|
|Script Name|String|True|TEST CLOSE|

## Google Chronicle Alerts Creator Job - 1
This job will sync new SOAR alerts with Chronicle SIEM.
Note: This job is only supported from Chronicle SOAR version 6.2.30 and higher.


**Run Interval In Seconds:** 60

#### Parameters
|Name|Type|Is Mandatory|Value|
|----|----|------------|-----|
|User's Service Account|Password||*****|
|Workload Identity Email|Password||*****|
|Environment|String|True|Default Environment|
|API Root|String|True|https://backstory.googleapis.com|
|Verify SSL|Boolean||true|

## Google Chronicle Alerts Creator Job - 13
This job will sync new SOAR alerts with Chronicle SIEM.
Note: This job is only supported from Chronicle SOAR version 6.2.30 and higher.


**Run Interval In Seconds:** 60

#### Parameters
|Name|Type|Is Mandatory|Value|
|----|----|------------|-----|
|User's Service Account|Password||*****|
|Workload Identity Email|Password||*****|
|Environment|String|True|Default Environment|
|API Root|String|True|https://backstory.googleapis.com|
|Verify SSL|Boolean||true|

## Google Chronicle Alerts Creator Job - 5
This job will sync new SOAR alerts with Chronicle SIEM.
Note: This job is only supported from Chronicle SOAR version 6.2.30 and higher.


**Run Interval In Seconds:** 60

#### Parameters
|Name|Type|Is Mandatory|Value|
|----|----|------------|-----|
|User's Service Account|Password||*****|
|Workload Identity Email|Password||*****|
|Environment|String|True|Default Environment|
|API Root|String|True|https://backstory.googleapis.com|
|Verify SSL|Boolean||false|

## Google Chronicle Sync Job - 1
This job will synchronize information about Chronicle SOAR Cases and Chronicle SOAR Alerts with Chronicle SIEM.
 Note: This job is only supported from Chronicle SOAR version 6.1.44 and higher.


**Run Interval In Seconds:** 60

#### Parameters
|Name|Type|Is Mandatory|Value|
|----|----|------------|-----|
|User's Service Account|Password||*****|
|Workload Identity Email|Password||*****|
|Environment|String|True|Default Environment|
|API Root|String|True|https://backstory.googleapis.com|
|Max Hours Backwards|String||24|
|Verify SSL|Boolean||true|

## Google Chronicle Sync Job - 2
This job will synchronize information about Chronicle SOAR Cases and Chronicle SOAR Alerts with Chronicle SIEM.
 Note: This job is only supported from Chronicle SOAR version 6.1.44 and higher.


**Run Interval In Seconds:** 60

#### Parameters
|Name|Type|Is Mandatory|Value|
|----|----|------------|-----|
|User's Service Account|Password||*****|
|Workload Identity Email|Password||*****|
|Environment|String|True|Default Environment|
|API Root|String|True|https://backstory.googleapis.com|
|Max Hours Backwards|String||24|
|Verify SSL|Boolean||false|

## Google Chronicle Sync Job -21
This job will synchronize information about Chronicle SOAR Cases and Chronicle SOAR Alerts with Chronicle SIEM.
 Note: This job is only supported from Chronicle SOAR version 6.1.44 and higher.


**Run Interval In Seconds:** 60

#### Parameters
|Name|Type|Is Mandatory|Value|
|----|----|------------|-----|
|Workload Identity Email|Password||*****|
|User's Service Account|Password||*****|
|Environment|String|True|Default Environment|
|API Root|String|True|https://backstory.googleapis.com|
|Max Hours Backwards|String||24|
|Verify SSL|Boolean||true|

## Refresh Token Renewal Job - 1
Token renewal job should be used to periodically update the refresh token configured for the integration. By default, the refresh token expires every 90 days, making integration unusable upon expiration. It is recommended to run this job every 7 or 14 days to make sure that refresh token will be up to date.


**Run Interval In Seconds:** 60

#### Parameters
|Name|Type|Is Mandatory|Value|
|----|----|------------|-----|
|Integration Environments|String||jhjhjh|
|Connector Names|String||m,nmnmnnm|

## Refresh Token Renewal Job - 4
Token renewal job should be used to periodically update the refresh token configured for the integration. By default, the refresh token expires every 90 days, making integration unusable upon expiration. It is recommended to run this job every 7 or 14 days to make sure that refresh token will be up to date.


**Run Interval In Seconds:** 60

#### Parameters
|Name|Type|Is Mandatory|Value|
|----|----|------------|-----|
|Integration Environments|String||sddssdsd|

## Refresh Token Renewal Job - 8
Token renewal job should be used to periodically update the refresh token configured for the integration. By default, the refresh token expires every 90 days, making integration unusable upon expiration. It is recommended to run this job every 7 or 14 days to make sure that refresh token will be up to date.


**Run Interval In Seconds:** 60

#### Parameters
|Name|Type|Is Mandatory|Value|
|----|----|------------|-----|
|Integration Environments|String||dssdsdsdsd|
|Connector Names|String||dsd|

## Refresh Token Renewal Job
Token renewal job should be used to periodically update the refresh token configured for the integration. By default, the refresh token expires every 90 days, making integration unusable upon expiration. It is recommended to run this job every 7 or 14 days to make sure that refresh token will be up to date.


**Run Interval In Seconds:** 60

#### Parameters
|Name|Type|Is Mandatory|Value|
|----|----|------------|-----|
|Integration Environments|String||dsddss|
|Connector Names|String||dsdsdds|

## Service Sync Closed Incidents
This job will synchronize closed ServiceNow incidents and Google SecOps alerts. This job works with ServiceNow incidents that were ingested as alerts and also cases, which contains tag “ServiceNow” and “TICKET_ID” context value with Incident Number inside of it.


**Run Interval In Seconds:** 60

#### Parameters
|Name|Type|Is Mandatory|Value|
|----|----|------------|-----|
|Api Root|String|True|https://{dev-instance}.service-now.com/api/now/v1/|
|Username|String|True|dsdssdds|
|Verify SSL|Boolean||true|
|Client ID|String||sdssddsds|
|Use Oauth Authentication|Boolean||false|
|Max Hours Backwards|Integer||24|
|Table Name|String|True|ddssdsd|
|Password|Password|True|*****|
|Client Secret|Password||*****|
|Refresh Token|Password||*****|

## Sync Alerts - 1
This job will synchronize Google SecOps Alerts and Crowdstrike alerts. The job synchronizes comments and status. Requires “Crowdstrike Alert” tag on the case. Note: If the alert didn’t originate from “Alerts Connector” or “Identity Protections Detection Connector” you will need to add an “Alert_ID” context value for the job to be able to find the correct information.


**Run Interval In Seconds:** 60

#### Parameters
|Name|Type|Is Mandatory|Value|
|----|----|------------|-----|
|Environment Name|String|True|Default Environment|
|API Root|String|True|https://api.crowdstrike.com|
|Client ID|String|True|kjhjkkjkj|
|Max Hours Backwards|Integer||24|
|Verify SSL|Boolean||true|
|Client Secret|Password|True|*****|

## Sync Alerts - 10
This job will synchronize Google SecOps Alerts and Crowdstrike alerts. The job synchronizes comments and status. Requires “Crowdstrike Alert” tag on the case. Note: If the alert didn’t originate from “Alerts Connector” or “Identity Protections Detection Connector” you will need to add an “Alert_ID” context value for the job to be able to find the correct information.


**Run Interval In Seconds:** 60

#### Parameters
|Name|Type|Is Mandatory|Value|
|----|----|------------|-----|
|Environment Name|String|True|Default Environment|
|API Root|String|True|https://api.crowdstrike.com|
|Client ID|String|True|ssdsdssd|
|Max Hours Backwards|Integer||24|
|Verify SSL|Boolean||false|
|Client Secret|Password|True|*****|

## Sync Alerts - 12
This job will synchronize Google SecOps Alerts and Crowdstrike alerts. The job synchronizes comments and status. Requires “Crowdstrike Alert” tag on the case. Note: If the alert didn’t originate from “Alerts Connector” or “Identity Protections Detection Connector” you will need to add an “Alert_ID” context value for the job to be able to find the correct information.


**Run Interval In Seconds:** 60

#### Parameters
|Name|Type|Is Mandatory|Value|
|----|----|------------|-----|
|Environment Name|String|True|Default Environment|
|API Root|String|True|https://api.crowdstrike.com|
|Client ID|String|True|dssdsdds|
|Max Hours Backwards|Integer||24|
|Verify SSL|Boolean||true|
|Client Secret|Password|True|*****|

## Sync Alerts - 15
This job will synchronize Google SecOps Alerts and SentinelOne alerts. The job synchronizes status. Requires “SentinelOne Alert” tag on the case. Note: If the alert didn’t originate from “Alerts Connector” you will need to add an “Alert_ID” Alert Context Value for the job to be able to find the correct information.


**Run Interval In Seconds:** 60

#### Parameters
|Name|Type|Is Mandatory|Value|
|----|----|------------|-----|
|Environment Name|String|True|Default Environment|
|API Root|String|True|dssdsddsd|
|Max Hours Backwards|Integer||24|
|Verify SSL|Boolean||true|
|API Token|Password|True|*****|

## Sync Alerts - 16
This job will synchronize Google SecOps Alerts and SentinelOne alerts. The job synchronizes status. Requires “SentinelOne Alert” tag on the case. Note: If the alert didn’t originate from “Alerts Connector” you will need to add an “Alert_ID” Alert Context Value for the job to be able to find the correct information.


**Run Interval In Seconds:** 60

#### Parameters
|Name|Type|Is Mandatory|Value|
|----|----|------------|-----|
|Environment Name|String|True|Default Environment|
|API Root|String|True|sdssdds|
|Max Hours Backwards|Integer||24|
|Verify SSL|Boolean||false|
|API Token|Password|True|*****|

## Sync Alerts - 17
This job will synchronize Google SecOps Alerts and SentinelOne alerts. The job synchronizes status. Requires “SentinelOne Alert” tag on the case. Note: If the alert didn’t originate from “Alerts Connector” you will need to add an “Alert_ID” Alert Context Value for the job to be able to find the correct information.


**Run Interval In Seconds:** 60

#### Parameters
|Name|Type|Is Mandatory|Value|
|----|----|------------|-----|
|Environment Name|String|True|Default Environment|
|API Root|String|True|cxcxcx|
|Max Hours Backwards|Integer||24|
|Verify SSL|Boolean||true|
|API Token|Password|True|*****|

## Sync Alerts - 22d
This job will synchronize Google SecOps Alerts and Crowdstrike alerts. The job synchronizes comments and status. Requires “Crowdstrike Alert” tag on the case. Note: If the alert didn’t originate from “Alerts Connector” or “Identity Protections Detection Connector” you will need to add an “Alert_ID” context value for the job to be able to find the correct information.


**Run Interval In Seconds:** 60

#### Parameters
|Name|Type|Is Mandatory|Value|
|----|----|------------|-----|
|Environment Name|String|True|Default Environment|
|API Root|String|True|https://api.crowdstrike.com|
|Client ID|String|True|ssddsdssd|
|Max Hours Backwards|Integer||24|
|Verify SSL|Boolean||true|
|Client Secret|Password|True|*****|

## Sync Alerts - 3
This job will synchronize Google SecOps Alerts and Crowdstrike alerts. The job synchronizes comments and status. Requires “Crowdstrike Alert” tag on the case. Note: If the alert didn’t originate from “Alerts Connector” or “Identity Protections Detection Connector” you will need to add an “Alert_ID” context value for the job to be able to find the correct information.


**Run Interval In Seconds:** 60

#### Parameters
|Name|Type|Is Mandatory|Value|
|----|----|------------|-----|
|Environment Name|String|True|Default Environment|
|API Root|String|True|https://api.crowdstrike.com|
|Client ID|String|True|ssdsssd|
|Max Hours Backwards|Integer||24|
|Verify SSL|Boolean||false|
|Client Secret|Password|True|*****|

## Sync Alerts - 4
This job will synchronize Google SecOps Alerts and Crowdstrike alerts. The job synchronizes comments and status. Requires “Crowdstrike Alert” tag on the case. Note: If the alert didn’t originate from “Alerts Connector” or “Identity Protections Detection Connector” you will need to add an “Alert_ID” context value for the job to be able to find the correct information.


**Run Interval In Seconds:** 60

#### Parameters
|Name|Type|Is Mandatory|Value|
|----|----|------------|-----|
|Environment Name|String|True|Default Environment|
|API Root|String|True|https://api.crowdstrike.com|
|Client ID|String|True|sddssd|
|Max Hours Backwards|Integer||24|
|Verify SSL|Boolean||true|
|Client Secret|Password|True|*****|

## Sync Alerts - 5
This job will synchronize Google SecOps Alerts and SentinelOne alerts. The job synchronizes status. Requires “SentinelOne Alert” tag on the case. Note: If the alert didn’t originate from “Alerts Connector” you will need to add an “Alert_ID” Alert Context Value for the job to be able to find the correct information.


**Run Interval In Seconds:** 60

#### Parameters
|Name|Type|Is Mandatory|Value|
|----|----|------------|-----|
|Environment Name|String|True|Default Environment|
|API Root|String|True|ssdssd|
|Max Hours Backwards|Integer||24|
|Verify SSL|Boolean||true|
|API Token|Password|True|*****|

## Sync Alerts - 6
This job will synchronize Google SecOps Alerts and Crowdstrike alerts. The job synchronizes comments and status. Requires “Crowdstrike Alert” tag on the case. Note: If the alert didn’t originate from “Alerts Connector” or “Identity Protections Detection Connector” you will need to add an “Alert_ID” context value for the job to be able to find the correct information.


**Run Interval In Seconds:** 60

#### Parameters
|Name|Type|Is Mandatory|Value|
|----|----|------------|-----|
|Environment Name|String|True|Default Environment|
|API Root|String|True|https://api.crowdstrike.com|
|Client ID|String|True|sdssddsds|
|Max Hours Backwards|Integer||24|
|Verify SSL|Boolean||false|
|Client Secret|Password|True|*****|

## Sync Alerts - 8
This job will synchronize Google SecOps Alerts and Crowdstrike alerts. The job synchronizes comments and status. Requires “Crowdstrike Alert” tag on the case. Note: If the alert didn’t originate from “Alerts Connector” or “Identity Protections Detection Connector” you will need to add an “Alert_ID” context value for the job to be able to find the correct information.


**Run Interval In Seconds:** 60

#### Parameters
|Name|Type|Is Mandatory|Value|
|----|----|------------|-----|
|Environment Name|String|True|Default Environment|
|API Root|String|True|https://api.crowdstrike.com|
|Client ID|String|True|qwewwewwe|
|Max Hours Backwards|Integer||24|
|Verify SSL|Boolean||false|
|Client Secret|Password|True|*****|

## Sync Alerts - 9
This job will synchronize Google SecOps Alerts and SentinelOne alerts. The job synchronizes status. Requires “SentinelOne Alert” tag on the case. Note: If the alert didn’t originate from “Alerts Connector” you will need to add an “Alert_ID” Alert Context Value for the job to be able to find the correct information.


**Run Interval In Seconds:** 60

#### Parameters
|Name|Type|Is Mandatory|Value|
|----|----|------------|-----|
|Environment Name|String|True|Default Environment|
|API Root|String|True|sdsddssdsd|
|Max Hours Backwards|Integer||24|
|Verify SSL|Boolean||false|
|API Token|Password|True|*****|

## Sync Alerts
This job will synchronize Google SecOps Alerts and Crowdstrike alerts. The job synchronizes comments and status. Requires “Crowdstrike Alert” tag on the case. Note: If the alert didn’t originate from “Alerts Connector” or “Identity Protections Detection Connector” you will need to add an “Alert_ID” context value for the job to be able to find the correct information.


**Run Interval In Seconds:** 60

#### Parameters
|Name|Type|Is Mandatory|Value|
|----|----|------------|-----|
|Environment Name|String|True|Default Environment|
|API Root|String|True|https://api.crowdstrike.com|
|Client ID|String|True|ssdsdasd|
|Max Hours Backwards|Integer||24|
|Verify SSL|Boolean||true|
|Client Secret|Password|True|*****|

## Sync Closed Incidents - jaya
This job will synchronize closed ServiceNow incidents and Google SecOps alerts. This job works with ServiceNow incidents that were ingested as alerts and also cases, which contains tag “ServiceNow” and “TICKET_ID” context value with Incident Number inside of it.


**Run Interval In Seconds:** 60

#### Parameters
|Name|Type|Is Mandatory|Value|
|----|----|------------|-----|
|Api Root|String|True|https://{dev-instance}.service-now.com/api/now/v1/|
|Username|String|True|jhjhjhjjkkjkjjk|
|Password|Password|True|*****|
|Client Secret|Password||*****|
|Refresh Token|Password||*****|
|Verify SSL|Boolean||true|
|Client ID|String||jhhjjh|
|Use Oauth Authentication|Boolean||false|
|Max Hours Backwards|Integer||24|
|Table Name|String|True|jkjkkjkj|

## Sync Closure
Close tickets in Jira if corresponding Google SecOps alerts were closed.


**Run Interval In Seconds:** 60

#### Parameters
|Name|Type|Is Mandatory|Value|
|----|----|------------|-----|
|API Token|Password|True|*****|
|API Root|String|True|https://{jira_address}|
|Username|String||sdsdds|
|Environment|String|||
|Project Names|String|True|project names separated by comma|
|Days Backwards|String|True|1|

## Sync Comments - 19
Sync comments from CA Desk Manager to Siemplify.


**Run Interval In Seconds:** 60

#### Parameters
|Name|Type|Is Mandatory|Value|
|----|----|------------|-----|
|Password|Password|True|*****|
|API Root|String|True|http://x.x.x.x:<port>|
|Username|String|True|sdssddssd|
|Summery Field|String|True|summery.combo_name|
|Ticket Fields|String|True|summery.combo_name,customer.combo_name,category.sym,status.sym,priority.sym,active,log_agent.combo_name,assignee.combo_name,group.combo_name,affected_service.name,severity.sym,urgency.sym,impact.sym,problem.ref_num,resolution_code.sym,call_back_date,change.chg_ref_num,caused_by_chg.chg_ref_num,external_system_ticket,resolution_method.sym,symptom_code.sym,requested_by.combo_name,persistent_id,summary,description,open_date,last_mod_dt,resolve_date,close_date,ref_num|
|Script Name|String|True|Test|
|Ticket Type Field|Boolean||true|
|Analyst Type Field|Boolean||true|
|Time Stamp Field|Boolean||true|
|Timezone String|Boolean||true|

## Sync Comments - 2
Sync comments from CA Desk Manager to Siemplify.


**Run Interval In Seconds:** 60

#### Parameters
|Name|Type|Is Mandatory|Value|
|----|----|------------|-----|
|Password|Password|True|*****|
|API Root|String|True|http://x.x.x.x:<port>|
|Username|String|True|tyyuu|
|Summery Field|String|True|summery.combo_name|
|Ticket Fields|String|True|summery.combo_name,customer.combo_name,category.sym,status.sym,priority.sym,active,log_agent.combo_name,assignee.combo_name,group.combo_name,affected_service.name,severity.sym,urgency.sym,impact.sym,problem.ref_num,resolution_code.sym,call_back_date,change.chg_ref_num,caused_by_chg.chg_ref_num,external_system_ticket,resolution_method.sym,symptom_code.sym,requested_by.combo_name,persistent_id,summary,description,open_date,last_mod_dt,resolve_date,close_date,ref_num|
|Script Name|String|True|Test|
|Ticket Type Field|Boolean||true|
|Analyst Type Field|Boolean||true|
|Time Stamp Field|Boolean||true|
|Timezone String|Boolean||true|

## Sync Comments - 3
Sync comments from CA Desk Manager to Siemplify.


**Run Interval In Seconds:** 60

#### Parameters
|Name|Type|Is Mandatory|Value|
|----|----|------------|-----|
|Password|Password|True|*****|
|API Root|String|True|http://x.x.x.x:<port>|
|Username|String|True|dsdsds|
|Summery Field|String|True|summery.combo_name|
|Ticket Fields|String|True|summery.combo_name,customer.combo_name,category.sym,status.sym,priority.sym,active,log_agent.combo_name,assignee.combo_name,group.combo_name,affected_service.name,severity.sym,urgency.sym,impact.sym,problem.ref_num,resolution_code.sym,call_back_date,change.chg_ref_num,caused_by_chg.chg_ref_num,external_system_ticket,resolution_method.sym,symptom_code.sym,requested_by.combo_name,persistent_id,summary,description,open_date,last_mod_dt,resolve_date,close_date,ref_num|
|Script Name|String|True|Test|
|Ticket Type Field|Boolean||true|
|Analyst Type Field|Boolean||true|
|Time Stamp Field|Boolean||true|
|Timezone String|Boolean||true|

## Sync Comments - 4
Sync comments from CA Desk Manager to Siemplify.


**Run Interval In Seconds:** 60

#### Parameters
|Name|Type|Is Mandatory|Value|
|----|----|------------|-----|
|API Root|String|True|http://x.x.x.x:<port>|
|Username|String|True|dsdsds|
|Summery Field|String|True|summery.combo_name|
|Ticket Fields|String|True|summery.combo_name,customer.combo_name,category.sym,status.sym,priority.sym,active,log_agent.combo_name,assignee.combo_name,group.combo_name,affected_service.name,severity.sym,urgency.sym,impact.sym,problem.ref_num,resolution_code.sym,call_back_date,change.chg_ref_num,caused_by_chg.chg_ref_num,external_system_ticket,resolution_method.sym,symptom_code.sym,requested_by.combo_name,persistent_id,summary,description,open_date,last_mod_dt,resolve_date,close_date,ref_num|
|Script Name|String|True|Test|
|Password|Password|True|*****|
|Ticket Type Field|Boolean||true|
|Analyst Type Field|Boolean||true|
|Time Stamp Field|Boolean||true|
|Timezone String|Boolean||true|

## Sync Comments - 5
Sync comments from CA Desk Manager to Siemplify.


**Run Interval In Seconds:** 60

#### Parameters
|Name|Type|Is Mandatory|Value|
|----|----|------------|-----|
|Password|Password|True|*****|
|API Root|String|True|http://x.x.x.x:<port>|
|Username|String|True|ssdsddssd|
|Summery Field|String|True|summery.combo_name|
|Ticket Fields|String|True|summery.combo_name,customer.combo_name,category.sym,status.sym,priority.sym,active,log_agent.combo_name,assignee.combo_name,group.combo_name,affected_service.name,severity.sym,urgency.sym,impact.sym,problem.ref_num,resolution_code.sym,call_back_date,change.chg_ref_num,caused_by_chg.chg_ref_num,external_system_ticket,resolution_method.sym,symptom_code.sym,requested_by.combo_name,persistent_id,summary,description,open_date,last_mod_dt,resolve_date,close_date,ref_num|
|Script Name|String|True|Test|
|Ticket Type Field|Boolean||true|
|Analyst Type Field|Boolean||true|
|Time Stamp Field|Boolean||true|
|Timezone String|Boolean||true|

## Sync Comments - 6
Sync comments from CA Desk Manager to Siemplify.


**Run Interval In Seconds:** 60

#### Parameters
|Name|Type|Is Mandatory|Value|
|----|----|------------|-----|
|Password|Password|True|*****|
|API Root|String|True|http://x.x.x.x:<port>|
|Username|String|True|hghjjkhjh|
|Summery Field|String|True|summery.combo_name|
|Ticket Fields|String|True|summery.combo_name,customer.combo_name,category.sym,status.sym,priority.sym,active,log_agent.combo_name,assignee.combo_name,group.combo_name,affected_service.name,severity.sym,urgency.sym,impact.sym,problem.ref_num,resolution_code.sym,call_back_date,change.chg_ref_num,caused_by_chg.chg_ref_num,external_system_ticket,resolution_method.sym,symptom_code.sym,requested_by.combo_name,persistent_id,summary,description,open_date,last_mod_dt,resolve_date,close_date,ref_num|
|Script Name|String|True|Test|
|Ticket Type Field|Boolean||true|
|Analyst Type Field|Boolean||true|
|Time Stamp Field|Boolean||true|
|Timezone String|Boolean||true|

## Sync Comments - 7
Sync comments from CA Desk Manager to Siemplify.


**Run Interval In Seconds:** 60

#### Parameters
|Name|Type|Is Mandatory|Value|
|----|----|------------|-----|
|Password|Password|True|*****|
|API Root|String|True|http://x.x.x.x:<port>|
|Username|String|True|ddsdssdsd|
|Summery Field|String|True|summery.combo_name|
|Ticket Fields|String|True|summery.combo_name,customer.combo_name,category.sym,status.sym,priority.sym,active,log_agent.combo_name,assignee.combo_name,group.combo_name,affected_service.name,severity.sym,urgency.sym,impact.sym,problem.ref_num,resolution_code.sym,call_back_date,change.chg_ref_num,caused_by_chg.chg_ref_num,external_system_ticket,resolution_method.sym,symptom_code.sym,requested_by.combo_name,persistent_id,summary,description,open_date,last_mod_dt,resolve_date,close_date,ref_num|
|Script Name|String|True|Test|
|Ticket Type Field|Boolean||true|
|Analyst Type Field|Boolean||true|
|Time Stamp Field|Boolean||true|
|Timezone String|Boolean||true|

## Sync Comments - 8
Sync comments from CA Desk Manager to Siemplify.


**Run Interval In Seconds:** 60

#### Parameters
|Name|Type|Is Mandatory|Value|
|----|----|------------|-----|
|Password|Password|True|*****|
|API Root|String|True|http://x.x.x.x:<port>|
|Username|String|True|dedfdffddf|
|Summery Field|String|True|summery.combo_name|
|Ticket Fields|String|True|summery.combo_name,customer.combo_name,category.sym,status.sym,priority.sym,active,log_agent.combo_name,assignee.combo_name,group.combo_name,affected_service.name,severity.sym,urgency.sym,impact.sym,problem.ref_num,resolution_code.sym,call_back_date,change.chg_ref_num,caused_by_chg.chg_ref_num,external_system_ticket,resolution_method.sym,symptom_code.sym,requested_by.combo_name,persistent_id,summary,description,open_date,last_mod_dt,resolve_date,close_date,ref_num|
|Script Name|String|True|Test|
|Ticket Type Field|Boolean||true|
|Analyst Type Field|Boolean||true|
|Time Stamp Field|Boolean||true|
|Timezone String|Boolean||true|

## Sync Comments
Sync comments from CA Desk Manager to Siemplify.


**Run Interval In Seconds:** 60

#### Parameters
|Name|Type|Is Mandatory|Value|
|----|----|------------|-----|
|Ticket Fields|String|True|summery.combo_name,customer.combo_name,category.sym,status.sym,priority.sym,active,log_agent.combo_name,assignee.combo_name,group.combo_name,affected_service.name,severity.sym,urgency.sym,impact.sym,problem.ref_num,resolution_code.sym,call_back_date,change.chg_ref_num,caused_by_chg.chg_ref_num,external_system_ticket,resolution_method.sym,symptom_code.sym,requested_by.combo_name,persistent_id,summary,description,open_date,last_mod_dt,resolve_date,close_date,ref_num|
|Script Name|String|True|Test|
|Ticket Type Field|Boolean||true|
|Analyst Type Field|Boolean||true|
|Time Stamp Field|Boolean||true|
|Timezone String|Boolean||true|
|Password|Password|True|*****|
|API Root|String|True|http://x.x.x.x:<port>|
|Username|String|True|jj,skskjkj|
|Summery Field|String|True|summery.combo_name|

## Sync Incidents - 11
This job synchronizes Google SecOps Alerts and Palo Alto XDR Incidents. It ensures that comments and status are kept in sync between the two systems. For the job to identify the correct information, the Google SecOps case must have the "Palo Alto XDR Incident" tag. If the alert didn’t originate from "Palo Alto Cortex XDR Connector",  you will need to add an "Incident_ID" context value to the case for the job to be able to find the correct information.


**Run Interval In Seconds:** 60

#### Parameters
|Name|Type|Is Mandatory|Value|
|----|----|------------|-----|
|Environment Name|String|True|Default Environment|
|Api Root|String|||
|Api Key ID|String|True|sdssdsdsdsd|
|Max Hours Backwards|Integer|True|24|
|User Mapping JSON|String||{"Google SecOps Display Name": "XDR Username"}|
|Verify SSL|Boolean||true|
|Api Key|Password|True|*****|

## Sync Incidents - 111
This job synchronizes Google SecOps Alerts and Palo Alto XDR Incidents. It ensures that comments and status are kept in sync between the two systems. For the job to identify the correct information, the Google SecOps case must have the "Palo Alto XDR Incident" tag. If the alert didn’t originate from "Palo Alto Cortex XDR Connector",  you will need to add an "Incident_ID" context value to the case for the job to be able to find the correct information.


**Run Interval In Seconds:** 60

#### Parameters
|Name|Type|Is Mandatory|Value|
|----|----|------------|-----|
|Environment Name|String|True|Default Environment|
|Api Root|String|||
|Api Key ID|String|True|kjjkkjkj|
|Max Hours Backwards|Integer|True|24|
|User Mapping JSON|String||{"Google SecOps Display Name": "XDR Username"}|
|Verify SSL|Boolean||true|
|Api Key|Password|True|*****|

## Sync Incidents - 1s
This job synchronizes Google SecOps Alerts and Palo Alto XDR Incidents. It ensures that comments and status are kept in sync between the two systems. For the job to identify the correct information, the Google SecOps case must have the "Palo Alto XDR Incident" tag. If the alert didn’t originate from "Palo Alto Cortex XDR Connector",  you will need to add an "Incident_ID" context value to the case for the job to be able to find the correct information.


**Run Interval In Seconds:** 60

#### Parameters
|Name|Type|Is Mandatory|Value|
|----|----|------------|-----|
|Environment Name|String|True|Default Environment|
|Api Root|String|||
|Api Key ID|String|True|ss|
|Max Hours Backwards|Integer|True|24|
|User Mapping JSON|String||{"Google SecOps Display Name": "XDR Username"}|
|Verify SSL|Boolean||true|
|Api Key|Password|True|*****|

## Sync Incidents - 2
This job synchronizes Google SecOps Alerts and Palo Alto XDR Incidents. It ensures that comments and status are kept in sync between the two systems. For the job to identify the correct information, the Google SecOps case must have the "Palo Alto XDR Incident" tag. If the alert didn’t originate from "Palo Alto Cortex XDR Connector",  you will need to add an "Incident_ID" context value to the case for the job to be able to find the correct information.


**Run Interval In Seconds:** 60

#### Parameters
|Name|Type|Is Mandatory|Value|
|----|----|------------|-----|
|Environment Name|String|True|Default Environment|
|Api Root|String||dssdsdsdsd|
|Api Key ID|String|True|dsdssdsd|
|Max Hours Backwards|Integer|True|24|
|User Mapping JSON|String||{"Google SecOps Display Name": "XDR Username"}|
|Verify SSL|Boolean||false|
|Api Key|Password|True|*****|

## Sync Incidents - 22
This job synchronizes Google SecOps Alerts and Palo Alto XDR Incidents. It ensures that comments and status are kept in sync between the two systems. For the job to identify the correct information, the Google SecOps case must have the "Palo Alto XDR Incident" tag. If the alert didn’t originate from "Palo Alto Cortex XDR Connector",  you will need to add an "Incident_ID" context value to the case for the job to be able to find the correct information.


**Run Interval In Seconds:** 60

#### Parameters
|Name|Type|Is Mandatory|Value|
|----|----|------------|-----|
|Environment Name|String|True|Default Environment|
|Api Root|String||cxcxcxc|
|Api Key ID|String|True|sds|
|Max Hours Backwards|Integer|True|24|
|User Mapping JSON|String||{"Google SecOps Display Name": "XDR Username"}|
|Verify SSL|Boolean||true|
|Api Key|Password|True|*****|

## Sync Incidents - 3
This job synchronizes Google SecOps Alerts and Palo Alto XDR Incidents. It ensures that comments and status are kept in sync between the two systems. For the job to identify the correct information, the Google SecOps case must have the "Palo Alto XDR Incident" tag. If the alert didn’t originate from "Palo Alto Cortex XDR Connector",  you will need to add an "Incident_ID" context value to the case for the job to be able to find the correct information.


**Run Interval In Seconds:** 60

#### Parameters
|Name|Type|Is Mandatory|Value|
|----|----|------------|-----|
|Environment Name|String|True|Default Environment|
|Api Root|String|||
|Api Key ID|String|True|dssdsdsd|
|Max Hours Backwards|Integer|True|24|
|User Mapping JSON|String||{"Google SecOps Display Name": "XDR Username"}|
|Verify SSL|Boolean||true|
|Api Key|Password|True|*****|

## Sync Incidents - 7
This job synchronizes Google SecOps Alerts and Palo Alto XDR Incidents. It ensures that comments and status are kept in sync between the two systems. For the job to identify the correct information, the Google SecOps case must have the "Palo Alto XDR Incident" tag. If the alert didn’t originate from "Palo Alto Cortex XDR Connector",  you will need to add an "Incident_ID" context value to the case for the job to be able to find the correct information.


**Run Interval In Seconds:** 60

#### Parameters
|Name|Type|Is Mandatory|Value|
|----|----|------------|-----|
|Environment Name|String|True|Default Environment|
|Api Root|String||ssddsddsds|
|Api Key ID|String|True|dssdsd|
|Api Key|Password|True|*****|
|Max Hours Backwards|Integer|True|24|
|User Mapping JSON|String||{"Google SecOps Display Name": "XDR Username"}|
|Verify SSL|Boolean||false|

## Sync Incidents V2 - 20
Use the Sync Incidents V2 job to synchronize Google SecOps alerts with Microsoft Sentinel incidents. This job ensures that comments, statuses, and tags are synchronized bi-directionally between both systems. Note: Assignee and severity synchronization occurs exclusively from Microsoft Sentinel to Google SecOps. For the job to identify the correct information, the Google SecOps case must have the Microsoft Sentinel Incident tag. This job only works on alerts from the Microsoft Azure Sentinel Incident Connector v2.


**Run Interval In Seconds:** 60

#### Parameters
|Name|Type|Is Mandatory|Value|
|----|----|------------|-----|
|Environment Name|String|True|Default Environment|
|Azure Subscription ID|String|True|sddssd|
|Azure Active Directory ID|String|True|dssdsdsds|
|OAUTH2 Login Endpoint Url|String|True|https://login.microsoftonline.com|
|Management API Root|String|True|https://msdanagement.azure.com|
|Azure Resource Group|String|True|sdsdsds|
|Azure Sentinel Workspace Name|String|True|dssd|
|Client ID|String|True|dsdsdsdsdds|
|Max Hours Backwards|Integer||24|
|Sync Assignee|Boolean||false|
|Verify SSL|Boolean||true|
|Client Secret|Password|True|*****|

## Sync Incidents
This job synchronizes Google SecOps Alerts and Palo Alto XDR Incidents. It ensures that comments and status are kept in sync between the two systems. For the job to identify the correct information, the Google SecOps case must have the "Palo Alto XDR Incident" tag. If the alert didn’t originate from "Palo Alto Cortex XDR Connector",  you will need to add an "Incident_ID" context value to the case for the job to be able to find the correct information.


**Run Interval In Seconds:** 60

#### Parameters
|Name|Type|Is Mandatory|Value|
|----|----|------------|-----|
|Environment Name|String|True|Default Environment|
|Api Root|String|||
|Api Key ID|String|True|54|
|Max Hours Backwards|Integer|True|24|
|User Mapping JSON|String||{"Google SecOps Display Name": "XDR Username"}|
|Verify SSL|Boolean||false|
|Api Key|Password|True|*****|

## Sync Threats - 18
This job will synchronize Google SecOps Alerts and SentinelOne threats. The job synchronizes comments and status. Requires “SentinelOne Threat” tag on the case. Note: If the alert didn’t originate from “Threats Connector” you will need to add an “Threat_ID” Alert Context Value for the job to be able to find the correct information. 


**Run Interval In Seconds:** 60

#### Parameters
|Name|Type|Is Mandatory|Value|
|----|----|------------|-----|
|Environment Name|String|True|Default Environment|
|API Root|String|True|dsdsd|
|Max Hours Backwards|Integer|True|24|
|Verify SSL|Boolean||true|
|API Token|Password|True|*****|

## Sync Threats - 5
This job will synchronize Google SecOps Alerts and SentinelOne threats. The job synchronizes comments and status. Requires “SentinelOne Threat” tag on the case. Note: If the alert didn’t originate from “Threats Connector” you will need to add an “Threat_ID” Alert Context Value for the job to be able to find the correct information. 


**Run Interval In Seconds:** 60

#### Parameters
|Name|Type|Is Mandatory|Value|
|----|----|------------|-----|
|Environment Name|String|True|Default Environment|
|API Root|String|True|fddfdfdf|
|Max Hours Backwards|Integer|True|24|
|Verify SSL|Boolean||false|
|API Token|Password|True|*****|

## Sync Threats - 8
This job will synchronize Google SecOps Alerts and SentinelOne threats. The job synchronizes comments and status. Requires “SentinelOne Threat” tag on the case. Note: If the alert didn’t originate from “Threats Connector” you will need to add an “Threat_ID” Alert Context Value for the job to be able to find the correct information. 


**Run Interval In Seconds:** 60

#### Parameters
|Name|Type|Is Mandatory|Value|
|----|----|------------|-----|
|Environment Name|String|True|Default Environment|
|API Root|String|True|dssddfdf|
|Max Hours Backwards|Integer|True|24|
|Verify SSL|Boolean||false|
|API Token|Password|True|*****|

## Sync Threats
This job will synchronize Google SecOps Alerts and SentinelOne threats. The job synchronizes comments and status. Requires “SentinelOne Threat” tag on the case. Note: If the alert didn’t originate from “Threats Connector” you will need to add an “Threat_ID” Alert Context Value for the job to be able to find the correct information. 


**Run Interval In Seconds:** 60

#### Parameters
|Name|Type|Is Mandatory|Value|
|----|----|------------|-----|
|Environment Name|String|True|Default Environment|
|API Root|String|True|ssssdsd|
|Max Hours Backwards|Integer|True|24|
|Verify SSL|Boolean||false|
|API Token|Password|True|*****|

## Token Renewal Job - 2
Token renewal job should be used to periodically update the refresh token configured for the integration. By default, the refresh token expires every 90 days, making integration unusable upon expiration. It is recommended to run this job every 7 or 14 days to make sure that refresh token will be up to date.


**Run Interval In Seconds:** 60

#### Parameters
|Name|Type|Is Mandatory|Value|
|----|----|------------|-----|
|Integration Environments|String||hello|
|Connector Names|String||hello|

## Token Renewal Job - 4
Token renewal job should be used to periodically update the refresh token configured for the integration. By default, the refresh token expires every 90 days, making integration unusable upon expiration. It is recommended to run this job every 7 or 14 days to make sure that refresh token will be up to date.


**Run Interval In Seconds:** 60

#### Parameters
|Name|Type|Is Mandatory|Value|
|----|----|------------|-----|
|Integration Environments|String||dssddssdds|
|Connector Names|String||sddssd|

## Token Renewal Job
Token renewal job should be used to periodically update the refresh token configured for the integration. By default, the refresh token expires every 90 days, making integration unusable upon expiration. It is recommended to run this job every 7 or 14 days to make sure that refresh token will be up to date.


**Run Interval In Seconds:** 60

#### Parameters
|Name|Type|Is Mandatory|Value|
|----|----|------------|-----|
|Integration Environments|String||jkhhjkhjk|
|Connector Names|String|||

## jira new Sync Closure
Close tickets in Jira if corresponding Google SecOps alerts were closed.


**Run Interval In Seconds:** 60

#### Parameters
|Name|Type|Is Mandatory|Value|
|----|----|------------|-----|
|API Root|String|True|https://{jira_address}|
|Username|String|||
|Environment|String|||
|Project Names|String|True|project names separated by comma|
|Days Backwards|String|True|1|
|API Token|Password|True|*****|

