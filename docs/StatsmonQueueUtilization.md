# StatsmonQueueUtilization


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**allocated_pct** | **int** |  | [optional] 
**default_queue** | **bool** |  | [optional] 
**excess_weight** | **int** |  | [optional] 
**sla_class** | **str** |  | [optional] 
**utilization_pct** | **float** |  | [optional] 

## Example

```python
from graphiant_sdk.models.statsmon_queue_utilization import StatsmonQueueUtilization

# TODO update the JSON string below
json = "{}"
# create an instance of StatsmonQueueUtilization from a JSON string
statsmon_queue_utilization_instance = StatsmonQueueUtilization.from_json(json)
# print the JSON string representation of the object
print(StatsmonQueueUtilization.to_json())

# convert the object into a dict
statsmon_queue_utilization_dict = statsmon_queue_utilization_instance.to_dict()
# create an instance of StatsmonQueueUtilization from a dict
statsmon_queue_utilization_from_dict = StatsmonQueueUtilization.from_dict(statsmon_queue_utilization_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


