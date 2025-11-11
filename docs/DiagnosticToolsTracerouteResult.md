# DiagnosticToolsTracerouteResult


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**hops** | [**List[DiagnosticToolsHopInfo]**](DiagnosticToolsHopInfo.md) |  | [optional] 
**max_latency** | **float** | time in milliseconds (required) | [optional] 
**max_latency_host** | **str** | IPv4 or IPv6 address (required) | [optional] 
**max_path_mtu** | **int** | Path MTU (required) | [optional] 
**min_path_mtu** | **int** | Path MTU (required) | [optional] 
**result** | **str** | Success or Failed (required) | [optional] 
**stopped_time** | [**GoogleProtobufTimestamp**](GoogleProtobufTimestamp.md) |  | [optional] 

## Example

```python
from graphiant_sdk.models.diagnostic_tools_traceroute_result import DiagnosticToolsTracerouteResult

# TODO update the JSON string below
json = "{}"
# create an instance of DiagnosticToolsTracerouteResult from a JSON string
diagnostic_tools_traceroute_result_instance = DiagnosticToolsTracerouteResult.from_json(json)
# print the JSON string representation of the object
print(DiagnosticToolsTracerouteResult.to_json())

# convert the object into a dict
diagnostic_tools_traceroute_result_dict = diagnostic_tools_traceroute_result_instance.to_dict()
# create an instance of DiagnosticToolsTracerouteResult from a dict
diagnostic_tools_traceroute_result_from_dict = DiagnosticToolsTracerouteResult.from_dict(diagnostic_tools_traceroute_result_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


