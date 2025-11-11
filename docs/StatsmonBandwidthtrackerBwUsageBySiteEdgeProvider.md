# StatsmonBandwidthtrackerBwUsageBySiteEdgeProvider


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**device_id** | **int** |  | [optional] 
**device_name** | **str** |  | [optional] 
**provider_id** | **int** |  | [optional] 
**provider_name** | **str** |  | [optional] 
**usage_kbps** | **float** |  | [optional] 

## Example

```python
from graphiant_sdk.models.statsmon_bandwidthtracker_bw_usage_by_site_edge_provider import StatsmonBandwidthtrackerBwUsageBySiteEdgeProvider

# TODO update the JSON string below
json = "{}"
# create an instance of StatsmonBandwidthtrackerBwUsageBySiteEdgeProvider from a JSON string
statsmon_bandwidthtracker_bw_usage_by_site_edge_provider_instance = StatsmonBandwidthtrackerBwUsageBySiteEdgeProvider.from_json(json)
# print the JSON string representation of the object
print(StatsmonBandwidthtrackerBwUsageBySiteEdgeProvider.to_json())

# convert the object into a dict
statsmon_bandwidthtracker_bw_usage_by_site_edge_provider_dict = statsmon_bandwidthtracker_bw_usage_by_site_edge_provider_instance.to_dict()
# create an instance of StatsmonBandwidthtrackerBwUsageBySiteEdgeProvider from a dict
statsmon_bandwidthtracker_bw_usage_by_site_edge_provider_from_dict = StatsmonBandwidthtrackerBwUsageBySiteEdgeProvider.from_dict(statsmon_bandwidthtracker_bw_usage_by_site_edge_provider_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


