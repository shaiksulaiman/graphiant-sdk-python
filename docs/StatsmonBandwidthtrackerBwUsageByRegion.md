# StatsmonBandwidthtrackerBwUsageByRegion


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**region_id** | **int** |  | [optional] 
**region_name** | **str** |  | [optional] 
**site_count** | **int** |  | [optional] 
**usage_kbps** | **float** |  | [optional] 

## Example

```python
from graphiant_sdk.models.statsmon_bandwidthtracker_bw_usage_by_region import StatsmonBandwidthtrackerBwUsageByRegion

# TODO update the JSON string below
json = "{}"
# create an instance of StatsmonBandwidthtrackerBwUsageByRegion from a JSON string
statsmon_bandwidthtracker_bw_usage_by_region_instance = StatsmonBandwidthtrackerBwUsageByRegion.from_json(json)
# print the JSON string representation of the object
print(StatsmonBandwidthtrackerBwUsageByRegion.to_json())

# convert the object into a dict
statsmon_bandwidthtracker_bw_usage_by_region_dict = statsmon_bandwidthtracker_bw_usage_by_region_instance.to_dict()
# create an instance of StatsmonBandwidthtrackerBwUsageByRegion from a dict
statsmon_bandwidthtracker_bw_usage_by_region_from_dict = StatsmonBandwidthtrackerBwUsageByRegion.from_dict(statsmon_bandwidthtracker_bw_usage_by_region_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


