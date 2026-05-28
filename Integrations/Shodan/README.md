
# Shodan

Shodan is a search engine that lets the user find specific types of computers (webcams, routers, servers, etc.) connected to the internet using a variety of filters. 

Python Version - V3_11
#### Parameters
|Name|Description|IsMandatory|Type|DefaultValue|
|----|-----------|-----------|----|------------|
|API key||True|Password|*****|
|Verify SSL||False|Boolean||


#### Dependencies
| |
|-|
|TIPCommon-1.0.11-py2.py3-none-any.whl|
|urllib3-2.6.3-py3-none-any.whl|
|requests-2.32.4-py3-none-any.whl|
|certifi-2026.4.22-py3-none-any.whl|
|chardet-7.4.3-cp311-cp311-manylinux2014_x86_64.manylinux_2_17_x86_64.manylinux_2_28_x86_64.whl|
|idna-3.13-py3-none-any.whl|
|charset_normalizer-3.4.7-cp311-cp311-manylinux2014_x86_64.manylinux_2_17_x86_64.manylinux_2_28_x86_64.whl|


## Actions
#### DNS Resolve
Look up the IP address for the provided list of hostnames.
Timeout - 600 Seconds



#### Get Api Info
Returns information about the API plan belonging to the given API key.
Timeout - 600 Seconds



#### Scan A Network
Scan a network using Shodan
Timeout - 600 Seconds



#### DNS Reverse
Look up the hostnames that have been defined for the given list of IP addresses
Timeout - 600 Seconds



#### Search
Search the SHODAN database.
Timeout - 600 Seconds


|Name|Description|IsMandatory|Type|DefaultValue|
|----|-----------|-----------|----|------------|
|Search Query|Search query; identical syntax to the website. e.g. find Apache webservers located in Germany(apache country:'DE', city:'Berlin')|True|String||
|Facets|A comma-separated list of properties to get summary information on. Property names can also be in the format of 'property:count'. (i.e. country:100, city:5). More information can be found at https://developer.shodan.io/api |False|String||
|Set Minify|Whether to minify the banner and only return the important data|False|Boolean|false|



#### Get Ip Info
Get all available information on an IP
Timeout - 600 Seconds


|Name|Description|IsMandatory|Type|DefaultValue|
|----|-----------|-----------|----|------------|
|Return Historical Banners|True if all historical banners should be returned|False|Boolean|false|
|Set Minify|True to only return the list of ports and the general host information, no banners.|False|Boolean|false|



#### Ping
Test connectivity
Timeout - 600 Seconds



#### SearchForExploits
Search across a variety of data sources for exploits and use facets to get summary information.
Timeout - 600 Seconds


|Name|Description|IsMandatory|Type|DefaultValue|
|----|-----------|-----------|----|------------|
|Search Query|Search query used to search the database of known exploits.|True|String||
|Facets|A comma-separated list of properties to get summary information on. (i.e. port, source, author). More information can be found at https://developer.shodan.io/api|False|String||
|Page|The page number to page through results 100 at a time.|False|String||









