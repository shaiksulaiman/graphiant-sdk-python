# StatsmonV2BfdStatsSelector


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**if_index** | **int** |  | [optional] 
**peer_address** | **str** |  | [optional] 
**type** | **str** |  | [optional] 

## Example

```python
from graphiant_sdk.models.statsmon_v2_bfd_stats_selector import StatsmonV2BfdStatsSelector

# TODO update the JSON string below
json = "{}"
# create an instance of StatsmonV2BfdStatsSelector from a JSON string
statsmon_v2_bfd_stats_selector_instance = StatsmonV2BfdStatsSelector.from_json(json)
# print the JSON string representation of the object
print(StatsmonV2BfdStatsSelector.to_json())

# convert the object into a dict
statsmon_v2_bfd_stats_selector_dict = statsmon_v2_bfd_stats_selector_instance.to_dict()
# create an instance of StatsmonV2BfdStatsSelector from a dict
statsmon_v2_bfd_stats_selector_from_dict = StatsmonV2BfdStatsSelector.from_dict(statsmon_v2_bfd_stats_selector_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


