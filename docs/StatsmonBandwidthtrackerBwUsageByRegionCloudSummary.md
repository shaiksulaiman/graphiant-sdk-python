# StatsmonBandwidthtrackerBwUsageByRegionCloudSummary


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**bwusage_top_providers** | [**List[StatsmonBandwidthtrackerBwUsageByTopProviders]**](StatsmonBandwidthtrackerBwUsageByTopProviders.md) |  | [optional] 
**cloudusage_kbps** | **float** |  | [optional] 
**percent_changed** | **float** |  | [optional] 
**provider_count** | **int** |  | [optional] 
**providerusage_kbps** | **int** |  | [optional] 
**totusage_kbps** | **float** |  | [optional] 

## Example

```python
from graphiant_sdk.models.statsmon_bandwidthtracker_bw_usage_by_region_cloud_summary import StatsmonBandwidthtrackerBwUsageByRegionCloudSummary

# TODO update the JSON string below
json = "{}"
# create an instance of StatsmonBandwidthtrackerBwUsageByRegionCloudSummary from a JSON string
statsmon_bandwidthtracker_bw_usage_by_region_cloud_summary_instance = StatsmonBandwidthtrackerBwUsageByRegionCloudSummary.from_json(json)
# print the JSON string representation of the object
print(StatsmonBandwidthtrackerBwUsageByRegionCloudSummary.to_json())

# convert the object into a dict
statsmon_bandwidthtracker_bw_usage_by_region_cloud_summary_dict = statsmon_bandwidthtracker_bw_usage_by_region_cloud_summary_instance.to_dict()
# create an instance of StatsmonBandwidthtrackerBwUsageByRegionCloudSummary from a dict
statsmon_bandwidthtracker_bw_usage_by_region_cloud_summary_from_dict = StatsmonBandwidthtrackerBwUsageByRegionCloudSummary.from_dict(statsmon_bandwidthtracker_bw_usage_by_region_cloud_summary_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


