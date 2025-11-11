# StatsmonBandwidthtrackerBwUsageByRegionEdgeSummary


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**bwusage_top_sites** | [**List[StatsmonBandwidthtrackerBwUsageByTopSites]**](StatsmonBandwidthtrackerBwUsageByTopSites.md) |  | [optional] 
**edgeusage_kbps** | **float** |  | [optional] 
**percent_changed** | **float** |  | [optional] 
**site_count** | **int** |  | [optional] 
**totusage_kbps** | **float** |  | [optional] 

## Example

```python
from graphiant_sdk.models.statsmon_bandwidthtracker_bw_usage_by_region_edge_summary import StatsmonBandwidthtrackerBwUsageByRegionEdgeSummary

# TODO update the JSON string below
json = "{}"
# create an instance of StatsmonBandwidthtrackerBwUsageByRegionEdgeSummary from a JSON string
statsmon_bandwidthtracker_bw_usage_by_region_edge_summary_instance = StatsmonBandwidthtrackerBwUsageByRegionEdgeSummary.from_json(json)
# print the JSON string representation of the object
print(StatsmonBandwidthtrackerBwUsageByRegionEdgeSummary.to_json())

# convert the object into a dict
statsmon_bandwidthtracker_bw_usage_by_region_edge_summary_dict = statsmon_bandwidthtracker_bw_usage_by_region_edge_summary_instance.to_dict()
# create an instance of StatsmonBandwidthtrackerBwUsageByRegionEdgeSummary from a dict
statsmon_bandwidthtracker_bw_usage_by_region_edge_summary_from_dict = StatsmonBandwidthtrackerBwUsageByRegionEdgeSummary.from_dict(statsmon_bandwidthtracker_bw_usage_by_region_edge_summary_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


