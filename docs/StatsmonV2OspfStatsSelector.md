# StatsmonV2OspfStatsSelector


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**router_id** | **str** |  | [optional] 
**type** | **str** |  | [optional] 
**vrf** | **str** |  | [optional] 

## Example

```python
from graphiant_sdk.models.statsmon_v2_ospf_stats_selector import StatsmonV2OspfStatsSelector

# TODO update the JSON string below
json = "{}"
# create an instance of StatsmonV2OspfStatsSelector from a JSON string
statsmon_v2_ospf_stats_selector_instance = StatsmonV2OspfStatsSelector.from_json(json)
# print the JSON string representation of the object
print(StatsmonV2OspfStatsSelector.to_json())

# convert the object into a dict
statsmon_v2_ospf_stats_selector_dict = statsmon_v2_ospf_stats_selector_instance.to_dict()
# create an instance of StatsmonV2OspfStatsSelector from a dict
statsmon_v2_ospf_stats_selector_from_dict = StatsmonV2OspfStatsSelector.from_dict(statsmon_v2_ospf_stats_selector_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


