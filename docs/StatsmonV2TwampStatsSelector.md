# StatsmonV2TwampStatsSelector


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**circuit_name** | **str** |  | [optional] 
**device_id** | **int** |  | [optional] 
**interface_name** | **str** |  | [optional] 
**type** | **str** |  | [optional] 

## Example

```python
from graphiant_sdk.models.statsmon_v2_twamp_stats_selector import StatsmonV2TwampStatsSelector

# TODO update the JSON string below
json = "{}"
# create an instance of StatsmonV2TwampStatsSelector from a JSON string
statsmon_v2_twamp_stats_selector_instance = StatsmonV2TwampStatsSelector.from_json(json)
# print the JSON string representation of the object
print(StatsmonV2TwampStatsSelector.to_json())

# convert the object into a dict
statsmon_v2_twamp_stats_selector_dict = statsmon_v2_twamp_stats_selector_instance.to_dict()
# create an instance of StatsmonV2TwampStatsSelector from a dict
statsmon_v2_twamp_stats_selector_from_dict = StatsmonV2TwampStatsSelector.from_dict(statsmon_v2_twamp_stats_selector_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


