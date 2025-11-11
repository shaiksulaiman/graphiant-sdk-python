# StatsmonV2CircuitSummary


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**average_delay** | **float** | Average delay for this circuit in this time duration | [optional] 
**average_jitter** | **float** | Average jitter for this circuit in this time duration | [optional] 
**average_link_down_speed_kbps** | **float** |  | [optional] 
**average_link_up_speed_kbps** | **float** |  | [optional] 
**average_loss** | **float** | Average loss for this circuit in this time duration | [optional] 
**avg_mos** | **float** | Graphiant avg score/QoE based on mos for the time duration | [optional] 
**circuit_name** | **str** |  | [optional] 
**config_link_down_speed_mbps** | **int** |  | [optional] 
**config_link_up_speed_mbps** | **int** |  | [optional] 
**connection_status** | **str** |  | [optional] 
**current_link_down_speed_kbps** | **float** |  | [optional] 
**current_link_up_speed_kbps** | **float** |  | [optional] 
**delay** | **int** | Delay in nano seconds | [optional] 
**jitter** | **int** | Jitter in nano seconds | [optional] 
**last_resort** | **bool** |  | [optional] 
**loss** | **float** | Loss in percentage | [optional] 
**max_delay** | **float** | Max delay for this circuit in this time duration | [optional] 
**max_jitter** | **float** | Max jitter for this circuit in this time duration | [optional] 
**max_loss** | **float** | Max loss for this circuit in this time duration | [optional] 
**max_mos** | **float** | Graphiant max score/QoE based on mos for the time duration | [optional] 
**min_delay** | **float** | Min delay for this circuit in this time duration | [optional] 
**min_jitter** | **float** | Min jitter for this circuit in this time duration | [optional] 
**min_loss** | **float** | Min loss for this circuit in this time duration | [optional] 
**min_mos** | **float** | Graphiant min score/QoE based on mos for the time duration | [optional] 
**mos** | **float** | Graphiant score/QoE based on mos | [optional] 

## Example

```python
from graphiant_sdk.models.statsmon_v2_circuit_summary import StatsmonV2CircuitSummary

# TODO update the JSON string below
json = "{}"
# create an instance of StatsmonV2CircuitSummary from a JSON string
statsmon_v2_circuit_summary_instance = StatsmonV2CircuitSummary.from_json(json)
# print the JSON string representation of the object
print(StatsmonV2CircuitSummary.to_json())

# convert the object into a dict
statsmon_v2_circuit_summary_dict = statsmon_v2_circuit_summary_instance.to_dict()
# create an instance of StatsmonV2CircuitSummary from a dict
statsmon_v2_circuit_summary_from_dict = StatsmonV2CircuitSummary.from_dict(statsmon_v2_circuit_summary_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


