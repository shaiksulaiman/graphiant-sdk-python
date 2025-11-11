# StatsmonBandwidthtrackerBwUsageBySite


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**edge_count** | **int** |  | [optional] 
**location_id** | **int** |  | [optional] 
**location_name** | **str** |  | [optional] 
**site_id** | **int** |  | [optional] 
**site_name** | **str** |  | [optional] 
**usage_kbps** | **float** |  | [optional] 

## Example

```python
from graphiant_sdk.models.statsmon_bandwidthtracker_bw_usage_by_site import StatsmonBandwidthtrackerBwUsageBySite

# TODO update the JSON string below
json = "{}"
# create an instance of StatsmonBandwidthtrackerBwUsageBySite from a JSON string
statsmon_bandwidthtracker_bw_usage_by_site_instance = StatsmonBandwidthtrackerBwUsageBySite.from_json(json)
# print the JSON string representation of the object
print(StatsmonBandwidthtrackerBwUsageBySite.to_json())

# convert the object into a dict
statsmon_bandwidthtracker_bw_usage_by_site_dict = statsmon_bandwidthtracker_bw_usage_by_site_instance.to_dict()
# create an instance of StatsmonBandwidthtrackerBwUsageBySite from a dict
statsmon_bandwidthtracker_bw_usage_by_site_from_dict = StatsmonBandwidthtrackerBwUsageBySite.from_dict(statsmon_bandwidthtracker_bw_usage_by_site_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


