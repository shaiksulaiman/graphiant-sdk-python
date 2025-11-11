# DiagnosticToolsSpeedtestServer


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**country** | **str** | Country of the speedtest server (required) | [optional] 
**host** | **str** | Hostname of the speedtest server (required) | [optional] 
**id** | **str** | Server Id. Internal mapping to a server. | [optional] 
**ip_address** | **str** | IPv4 or IPv6 address (required) | [optional] 
**location** | **str** | Location of the speedtest server (required) | [optional] 
**name** | **str** | Name of the speedtest server (required) | [optional] 

## Example

```python
from graphiant_sdk.models.diagnostic_tools_speedtest_server import DiagnosticToolsSpeedtestServer

# TODO update the JSON string below
json = "{}"
# create an instance of DiagnosticToolsSpeedtestServer from a JSON string
diagnostic_tools_speedtest_server_instance = DiagnosticToolsSpeedtestServer.from_json(json)
# print the JSON string representation of the object
print(DiagnosticToolsSpeedtestServer.to_json())

# convert the object into a dict
diagnostic_tools_speedtest_server_dict = diagnostic_tools_speedtest_server_instance.to_dict()
# create an instance of DiagnosticToolsSpeedtestServer from a dict
diagnostic_tools_speedtest_server_from_dict = DiagnosticToolsSpeedtestServer.from_dict(diagnostic_tools_speedtest_server_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


