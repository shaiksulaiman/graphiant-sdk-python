# StatsmonV2QueueUtilization


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**allocated_pct** | **int** |  | [optional] 
**default_queue** | **bool** |  | [optional] 
**excess_weight** | **int** |  | [optional] 
**sla_class** | **str** |  | [optional] 
**utilization_kbps** | **float** |  | [optional] 
**utilization_pct** | **float** |  | [optional] 

## Example

```python
from graphiant_sdk.models.statsmon_v2_queue_utilization import StatsmonV2QueueUtilization

# TODO update the JSON string below
json = "{}"
# create an instance of StatsmonV2QueueUtilization from a JSON string
statsmon_v2_queue_utilization_instance = StatsmonV2QueueUtilization.from_json(json)
# print the JSON string representation of the object
print(StatsmonV2QueueUtilization.to_json())

# convert the object into a dict
statsmon_v2_queue_utilization_dict = statsmon_v2_queue_utilization_instance.to_dict()
# create an instance of StatsmonV2QueueUtilization from a dict
statsmon_v2_queue_utilization_from_dict = StatsmonV2QueueUtilization.from_dict(statsmon_v2_queue_utilization_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


