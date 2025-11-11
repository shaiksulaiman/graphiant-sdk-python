# DiagnosticToolsDiagnosticParams


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**dest_address** | **str** | IPv4 or IPv6 Destination address (required) | 
**hop_stats_count** | **int** | Per hop probes needed for traceroute hop stats | [optional] 
**interface** | **str** | Source Interface name | [optional] 
**payload_size** | **int** | Size of  packet to be sent | [optional] 
**port** | **int** | Valid in case of TCP ping (required) | 
**probe_count** | **int** | Number of probes to send | [optional] 
**src_address** | **str** | IPv4 or IPv6 address (required) | 
**tos** | **int** | Type of service | [optional] 
**vrf_name** | **str** | configure VRF Name (required) | 

## Example

```python
from graphiant_sdk.models.diagnostic_tools_diagnostic_params import DiagnosticToolsDiagnosticParams

# TODO update the JSON string below
json = "{}"
# create an instance of DiagnosticToolsDiagnosticParams from a JSON string
diagnostic_tools_diagnostic_params_instance = DiagnosticToolsDiagnosticParams.from_json(json)
# print the JSON string representation of the object
print(DiagnosticToolsDiagnosticParams.to_json())

# convert the object into a dict
diagnostic_tools_diagnostic_params_dict = diagnostic_tools_diagnostic_params_instance.to_dict()
# create an instance of DiagnosticToolsDiagnosticParams from a dict
diagnostic_tools_diagnostic_params_from_dict = DiagnosticToolsDiagnosticParams.from_dict(diagnostic_tools_diagnostic_params_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


