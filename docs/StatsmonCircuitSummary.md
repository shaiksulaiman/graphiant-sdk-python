# StatsmonCircuitSummary


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**admin_status** | **bool** |  | [optional] 
**average_link_down_speed_kbps** | **float** |  | [optional] 
**average_link_up_speed_kbps** | **float** |  | [optional] 
**avg_mos** | **float** | Graphiant avg score/QoE based on mos for the time duration | [optional] 
**config_link_down_speed_mbps** | **int** |  | [optional] 
**config_link_up_speed_mbps** | **int** |  | [optional] 
**connection_status** | **str** |  | [optional] 
**current_link_down_speed_kbps** | **float** |  | [optional] 
**current_link_up_speed_kbps** | **float** |  | [optional] 
**delay** | **int** | Delay in nano seconds | [optional] 
**jitter** | **int** | Jitter in nano seconds | [optional] 
**loss** | **float** | Loss in percentage | [optional] 
**mos** | **float** | Graphiant score/QoE based on mos | [optional] 
**name** | **str** |  | [optional] 

## Example

```python
from graphiant_sdk.models.statsmon_circuit_summary import StatsmonCircuitSummary

# TODO update the JSON string below
json = "{}"
# create an instance of StatsmonCircuitSummary from a JSON string
statsmon_circuit_summary_instance = StatsmonCircuitSummary.from_json(json)
# print the JSON string representation of the object
print(StatsmonCircuitSummary.to_json())

# convert the object into a dict
statsmon_circuit_summary_dict = statsmon_circuit_summary_instance.to_dict()
# create an instance of StatsmonCircuitSummary from a dict
statsmon_circuit_summary_from_dict = StatsmonCircuitSummary.from_dict(statsmon_circuit_summary_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


