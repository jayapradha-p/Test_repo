
# Talos

Talos ThreatSource is a regular intelligence update from Cisco Talos, highlighting the biggest threats each week and other security news.

Python Version - V3_11
#### Parameters
|Name|Description|IsMandatory|Type|DefaultValue|
|----|-----------|-----------|----|------------|
|Use SSL||False|Boolean|False|


#### Dependencies
| |
|-|
|urllib3-2.6.3-py3-none-any.whl|
|requests-2.32.4-py3-none-any.whl|
|requests_file-3.0.1-py2.py3-none-any.whl|
|certifi-2026.4.22-py3-none-any.whl|
|TIPCommon-1.0.10-py3-none-any.whl|
|chardet-7.4.3-cp311-cp311-manylinux2014_x86_64.manylinux_2_17_x86_64.manylinux_2_28_x86_64.whl|
|tldextract-5.1.2-py3-none-any.whl|
|filelock-3.29.0-py3-none-any.whl|
|idna-3.13-py3-none-any.whl|
|charset_normalizer-3.4.7-cp311-cp311-manylinux2014_x86_64.manylinux_2_17_x86_64.manylinux_2_28_x86_64.whl|


## Actions
#### Get Reputation
Enrich entities using information from the Talos ThreatSource. Supported entities: IP Address, Hostname, URLs. Note: action takes the domain part from URL entities. Note: Action is running as async, please adjust script timeout value in Siemplify IDE for action as needed. Between each submission action waits, so that access won't be blocked.
Timeout - 600 Seconds



#### Whois
Retrieve Whois information about entities using Talos ThreatSource. Supported entities: IP Address, Hostname, URLs. Note: action takes the domain part from URL entities. Note: Action is running as async, please adjust script timeout value in Siemplify IDE for action as needed. Between each submission action waits, so that access won’t be blocked.
Timeout - 600 Seconds



#### Ping
Test Connectivity
Timeout - 600 Seconds









