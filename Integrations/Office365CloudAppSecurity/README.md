
# Office365CloudAppSecurity

Office 365 Cloud App Security is a subset of Microsoft Cloud App Security that provides CloudApp controls scoped to Office 365 environment. CloudApp controls for Office 365 enhances incident response efforts by providing a combination of in-depth visibility into user activity and automated governance actions based on defined policy.

Python Version - V3_11
#### Parameters
|Name|Description|IsMandatory|Type|DefaultValue|
|----|-----------|-----------|----|------------|
|portal URL||True|String||
|API token||True|Password|*****|


#### Dependencies
| |
|-|
|TIPCommon-1.0.11-py2.py3-none-any.whl|
|EnvironmentCommon-1.0.1-py2.py3-none-any.whl|
|urllib3-2.6.3-py3-none-any.whl|
|requests-2.32.4-py3-none-any.whl|
|certifi-2026.4.22-py3-none-any.whl|
|chardet-7.4.3-cp311-cp311-manylinux2014_x86_64.manylinux_2_17_x86_64.manylinux_2_28_x86_64.whl|
|idna-3.13-py3-none-any.whl|
|charset_normalizer-3.4.7-cp311-cp311-manylinux2014_x86_64.manylinux_2_17_x86_64.manylinux_2_28_x86_64.whl|


## Actions
#### Add IP To IP Address Range
Add IP address to IP address range in Microsoft Cloud App Security. Supported entities: IP address.
Timeout - 600 Seconds


|Name|Description|IsMandatory|Type|DefaultValue|
|----|-----------|-----------|----|------------|
|Name|Specify the name for the IP address range that needs to be updated.|True|String||



#### Ping
The action is used to test connectivity.
Timeout - 600 Seconds



#### Remove IP From IP Address Range
Remove IP address from IP address range in Microsoft Cloud App Security. Supported entities: IP address. Note: action can only remove exact matches. For example, action won't be able to remove 192.168.1.30, if in the range 192.168.1.1/24 was provided.
Timeout - 600 Seconds


|Name|Description|IsMandatory|Type|DefaultValue|
|----|-----------|-----------|----|------------|
|Name|Specify the name for the IP address range that needs to be updated.|True|String||



#### Close Alert
Close alert in Microsoft Cloud App Security.
Timeout - 600 Seconds


|Name|Description|IsMandatory|Type|DefaultValue|
|----|-----------|-----------|----|------------|
|Alert ID|Specify the ID of the alert that needs to be closed and marked as benign.|True|String||
|Comment|Specify a comment about why the alerts are closed and marked as benign.|False|String||
|State|Specify what should be the state of the alert.|True|List|True Positive|
|Reason|Specify a reason why the alert should be closed. Note: this parameter doesn't have an impact, if state is "True Positive".|False|List|No Reason|



#### Bulk Resolve Alert
Deprecated. Please refer to action "Close Alert".
Timeout - 600 Seconds


|Name|Description|IsMandatory|Type|DefaultValue|
|----|-----------|-----------|----|------------|
|Alert ID|Alert Unique Identifier. Can take multiple IDs which are comma separated|True|String||
|Comment|A comment to explain why alerts are resolved|False|String|Resolved|



#### Dismiss Alert
Deprecated. Please refer to action "Close Alert".
Timeout - 600 Seconds


|Name|Description|IsMandatory|Type|DefaultValue|
|----|-----------|-----------|----|------------|
|Alert ID|Alert Unique Identifier. The parameter takes single alert Ids|True|String||
|Comment|A comment to explain why an alert is dismissed|False|String||



#### List Files
List available files in Microsoft Cloud App Security.
Timeout - 600 Seconds


|Name|Description|IsMandatory|Type|DefaultValue|
|----|-----------|-----------|----|------------|
|Filter Key|Specify the key that needs to be used to filter files. Possible values for "File Type": Other, Document, Spreadsheet, Presentation, Text, Image, Folder. Possible values for "Share Status": Public (Internet), Public, External, Internal, Private.|False|List|Select One|
|Filter Logic|Specify what filter logic should be applied. Filtering logic is working based on the value  provided in the "Filter Key" parameter. Note: only File Name and ID work with Contains logic.|False|List|Not Specified|
|Filter Value|Specify what value should be used in the filter. If "Equal" is selected, action will try to find the exact match among results and if "Contains" is selected, action will try to find results that contain that substring. If nothing is provided in this parameter, the filter will not be applied. Filtering logic is working based on the value  provided in the "Filter Key" parameter.|False|String||
|Max Records To Return|Specify how many records to return. If nothing is provided, action will return 50 records. Note: for contains logic, action will only look at 1000 results for matching.|False|String|50|



#### Get User related activities
The action is used to view activities related to a user. The username of the user is used in this action.
Timeout - 600 Seconds


|Name|Description|IsMandatory|Type|DefaultValue|
|----|-----------|-----------|----|------------|
|Activity Display Limit|Limit on the number of activities to display|False|String|10|
|Time Frame|Specify the value to fetch the number of activities that occurred according to the specified value of hours ago|True|String|24|
|Product Name|Product list where the user can select an app connected to cloudapp security to enable them to get user related activities of a specific selected app. The product name is to be converted/mapped to the product code in the action filters Eg. if  Office 365 is selected should be converted to 11161|False|String|All|



#### Create IP Address Range
Create IP address range in Microsoft Cloud App Security.
Timeout - 600 Seconds


|Name|Description|IsMandatory|Type|DefaultValue|
|----|-----------|-----------|----|------------|
|Name|Specify the name for the IP address range.|True|String||
|Category|Specify the category for the IP address range.|True|List|Corporate|
|Organization|Specify the organization for the IP address range.|False|String||
|Subnets|Specify a comma-separated list of subnets for the IP address range.|True|String||
|Tags|Specify a comma-separated list of tags for the IP address range.|False|String||



#### Enrich Entities
Enrich entities using information from Microsoft Cloud App Security. Supported entities: Username.
Timeout - 600 Seconds



#### Get IP related activities
The action is used to view activities related to an IP.
Timeout - 600 Seconds


|Name|Description|IsMandatory|Type|DefaultValue|
|----|-----------|-----------|----|------------|
|Activity Display Limit|Limit on the number of activities to display|False|String|10|
|Product name|Product list where the user can select an app connected to cloudapp security to enable them to get IP related activities of a specific selected app. The product name is to be converted/mapped to the product code in the action filters. Eg. if  Office 365 is selected should be converted to 11161|False|String|All|
|Time Frame|Specify the value to fetch the number of activities that occurred according to the specified value of hours ago|True|String|24|









## Connectors
#### Office 365 CloudApp Security Connector
Fetches alerts from Office 365 CloudApp Security.

|Name|Description|IsMandatory|Type|DefaultValue|
|----|-----------|-----------|----|------------|
|Cloud App Security portal URL|The URL of the Office 365 CloudApp Security portal.|True|String||
|API Token|API Token that will be used to authenticate with Office 365 CloudApp Security.|True|Password|*****|
|Verify SSL|Verify SSL certificates for HTTPS requests to Office 365 CloudApp Security.|False|Boolean|false|
|Max Alerts Per Cycle|How many alerts should be processed during one connector run. Default: 5|True|Int|5|
|Offset Time In Hours|Number of hours before the first connector iteration to retrieve alerts from. This parameter applies to the initial connector iteration after you enable the connector for the first time, or used as a fallback value in cases where connector's last run timestamp expires. Default value: 24 hours.|True|Int|24|
|Alerts Padding Period|Time frame in minutes to search for new alerts backwards in time from the connector last run timestamp. Its recommended to adjust this value accordingly to the environment, for example 60 minutes.|False|Int|0|
|Environment Field Name|Describes the name of the field where the environment name is stored.|False|String||
|Environment Regex Pattern|If defined - the connector will implement the specific RegEx pattern on the data from "environment field" to extract specific string. For example - extract domain from sender's address: "(?<=@)(\S+$)"|False|Int||
|Proxy Server Address|The address of the proxy server to use.|False|String||
|Proxy Username|The proxy username to authenticate with.|False|String||
|Proxy Password|The proxy password to authenticate with.|False|Password|*****|




