# StatsmonBandwidthtrackerBwUsageByTopRegions


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**bwusage_role_summary** | [**List[StatsmonBandwidthtrackerBwUsageByRoleSummary]**](StatsmonBandwidthtrackerBwUsageByRoleSummary.md) |  | [optional] 
**region_id** | **int** |  | [optional] 
**region_name** | **str** |  | [optional] 

## Example

```python
from graphiant_sdk.models.statsmon_bandwidthtracker_bw_usage_by_top_regions import StatsmonBandwidthtrackerBwUsageByTopRegions

# TODO update the JSON string below
json = "{}"
# create an instance of StatsmonBandwidthtrackerBwUsageByTopRegions from a JSON string
statsmon_bandwidthtracker_bw_usage_by_top_regions_instance = StatsmonBandwidthtrackerBwUsageByTopRegions.from_json(json)
# print the JSON string representation of the object
print(StatsmonBandwidthtrackerBwUsageByTopRegions.to_json())

# convert the object into a dict
statsmon_bandwidthtracker_bw_usage_by_top_regions_dict = statsmon_bandwidthtracker_bw_usage_by_top_regions_instance.to_dict()
# create an instance of StatsmonBandwidthtrackerBwUsageByTopRegions from a dict
statsmon_bandwidthtracker_bw_usage_by_top_regions_from_dict = StatsmonBandwidthtrackerBwUsageByTopRegions.from_dict(statsmon_bandwidthtracker_bw_usage_by_top_regions_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


