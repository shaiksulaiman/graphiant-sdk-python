# DiagnosticToolsHopStats


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**avg_time** | **float** | Time in milli seconds (required) | [optional] 
**max_time** | **float** | Time in milli seconds (required) | [optional] 
**min_time** | **float** | Time in milli seconds (required) | [optional] 
**rx_packets** | **int** | Received packet count (required) | [optional] 
**std_dev_time** | **float** | Standard deviation of the round-trip time in milli seconds (required) | [optional] 
**tx_packets** | **int** | Transmitted packet count (required) | [optional] 

## Example

```python
from graphiant_sdk.models.diagnostic_tools_hop_stats import DiagnosticToolsHopStats

# TODO update the JSON string below
json = "{}"
# create an instance of DiagnosticToolsHopStats from a JSON string
diagnostic_tools_hop_stats_instance = DiagnosticToolsHopStats.from_json(json)
# print the JSON string representation of the object
print(DiagnosticToolsHopStats.to_json())

# convert the object into a dict
diagnostic_tools_hop_stats_dict = diagnostic_tools_hop_stats_instance.to_dict()
# create an instance of DiagnosticToolsHopStats from a dict
diagnostic_tools_hop_stats_from_dict = DiagnosticToolsHopStats.from_dict(diagnostic_tools_hop_stats_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


