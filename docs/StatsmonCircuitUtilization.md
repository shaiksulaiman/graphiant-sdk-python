# StatsmonCircuitUtilization


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**config_link_up_speed_mbps** | **int** |  | [optional] 
**name** | **str** |  | [optional] 
**queue_utilization** | [**List[StatsmonQueueUtilization]**](StatsmonQueueUtilization.md) |  | [optional] 

## Example

```python
from graphiant_sdk.models.statsmon_circuit_utilization import StatsmonCircuitUtilization

# TODO update the JSON string below
json = "{}"
# create an instance of StatsmonCircuitUtilization from a JSON string
statsmon_circuit_utilization_instance = StatsmonCircuitUtilization.from_json(json)
# print the JSON string representation of the object
print(StatsmonCircuitUtilization.to_json())

# convert the object into a dict
statsmon_circuit_utilization_dict = statsmon_circuit_utilization_instance.to_dict()
# create an instance of StatsmonCircuitUtilization from a dict
statsmon_circuit_utilization_from_dict = StatsmonCircuitUtilization.from_dict(statsmon_circuit_utilization_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


