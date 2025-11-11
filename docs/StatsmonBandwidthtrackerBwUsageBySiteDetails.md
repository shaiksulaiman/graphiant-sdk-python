# StatsmonBandwidthtrackerBwUsageBySiteDetails


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**bwuage_edge_provider** | [**List[StatsmonBandwidthtrackerBwUsageBySiteEdgeProvider]**](StatsmonBandwidthtrackerBwUsageBySiteEdgeProvider.md) |  | [optional] 
**bwuage_provider** | [**List[StatsmonBandwidthtrackerBwUsageBySiteProvider]**](StatsmonBandwidthtrackerBwUsageBySiteProvider.md) |  | [optional] 

## Example

```python
from graphiant_sdk.models.statsmon_bandwidthtracker_bw_usage_by_site_details import StatsmonBandwidthtrackerBwUsageBySiteDetails

# TODO update the JSON string below
json = "{}"
# create an instance of StatsmonBandwidthtrackerBwUsageBySiteDetails from a JSON string
statsmon_bandwidthtracker_bw_usage_by_site_details_instance = StatsmonBandwidthtrackerBwUsageBySiteDetails.from_json(json)
# print the JSON string representation of the object
print(StatsmonBandwidthtrackerBwUsageBySiteDetails.to_json())

# convert the object into a dict
statsmon_bandwidthtracker_bw_usage_by_site_details_dict = statsmon_bandwidthtracker_bw_usage_by_site_details_instance.to_dict()
# create an instance of StatsmonBandwidthtrackerBwUsageBySiteDetails from a dict
statsmon_bandwidthtracker_bw_usage_by_site_details_from_dict = StatsmonBandwidthtrackerBwUsageBySiteDetails.from_dict(statsmon_bandwidthtracker_bw_usage_by_site_details_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


