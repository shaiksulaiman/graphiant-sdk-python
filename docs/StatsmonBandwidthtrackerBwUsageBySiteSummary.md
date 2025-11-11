# StatsmonBandwidthtrackerBwUsageBySiteSummary


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**bwuage_region** | [**List[StatsmonBandwidthtrackerBwUsageByRegion]**](StatsmonBandwidthtrackerBwUsageByRegion.md) |  | [optional] 
**edge_count** | **int** |  | [optional] 
**provider_count** | **int** |  | [optional] 
**usage_kbps** | **float** |  | [optional] 

## Example

```python
from graphiant_sdk.models.statsmon_bandwidthtracker_bw_usage_by_site_summary import StatsmonBandwidthtrackerBwUsageBySiteSummary

# TODO update the JSON string below
json = "{}"
# create an instance of StatsmonBandwidthtrackerBwUsageBySiteSummary from a JSON string
statsmon_bandwidthtracker_bw_usage_by_site_summary_instance = StatsmonBandwidthtrackerBwUsageBySiteSummary.from_json(json)
# print the JSON string representation of the object
print(StatsmonBandwidthtrackerBwUsageBySiteSummary.to_json())

# convert the object into a dict
statsmon_bandwidthtracker_bw_usage_by_site_summary_dict = statsmon_bandwidthtracker_bw_usage_by_site_summary_instance.to_dict()
# create an instance of StatsmonBandwidthtrackerBwUsageBySiteSummary from a dict
statsmon_bandwidthtracker_bw_usage_by_site_summary_from_dict = StatsmonBandwidthtrackerBwUsageBySiteSummary.from_dict(statsmon_bandwidthtracker_bw_usage_by_site_summary_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


