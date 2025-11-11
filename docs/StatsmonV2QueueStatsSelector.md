# StatsmonV2QueueStatsSelector


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**group_name** | **str** |  | [optional] 
**interface_name** | **str** |  | [optional] 
**sla_class** | **str** |  | [optional] 
**type** | **str** |  | [optional] 

## Example

```python
from graphiant_sdk.models.statsmon_v2_queue_stats_selector import StatsmonV2QueueStatsSelector

# TODO update the JSON string below
json = "{}"
# create an instance of StatsmonV2QueueStatsSelector from a JSON string
statsmon_v2_queue_stats_selector_instance = StatsmonV2QueueStatsSelector.from_json(json)
# print the JSON string representation of the object
print(StatsmonV2QueueStatsSelector.to_json())

# convert the object into a dict
statsmon_v2_queue_stats_selector_dict = statsmon_v2_queue_stats_selector_instance.to_dict()
# create an instance of StatsmonV2QueueStatsSelector from a dict
statsmon_v2_queue_stats_selector_from_dict = StatsmonV2QueueStatsSelector.from_dict(statsmon_v2_queue_stats_selector_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


