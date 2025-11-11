# DiagnosticToolsHopInfo


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**host_address** | **str** | IPv4 or IPv6 address (required) | [optional] 
**path_mtu** | **int** | Path MTU for this host_address (required) | [optional] 
**round_trip_time** | **float** | time in milli seconds (required) | [optional] 
**stats** | [**DiagnosticToolsHopStats**](DiagnosticToolsHopStats.md) |  | [optional] 

## Example

```python
from graphiant_sdk.models.diagnostic_tools_hop_info import DiagnosticToolsHopInfo

# TODO update the JSON string below
json = "{}"
# create an instance of DiagnosticToolsHopInfo from a JSON string
diagnostic_tools_hop_info_instance = DiagnosticToolsHopInfo.from_json(json)
# print the JSON string representation of the object
print(DiagnosticToolsHopInfo.to_json())

# convert the object into a dict
diagnostic_tools_hop_info_dict = diagnostic_tools_hop_info_instance.to_dict()
# create an instance of DiagnosticToolsHopInfo from a dict
diagnostic_tools_hop_info_from_dict = DiagnosticToolsHopInfo.from_dict(diagnostic_tools_hop_info_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


