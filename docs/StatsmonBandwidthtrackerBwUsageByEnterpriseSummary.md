# StatsmonBandwidthtrackerBwUsageByEnterpriseSummary


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**bwusage_role_summary** | [**List[StatsmonBandwidthtrackerBwUsageByRoleSummary]**](StatsmonBandwidthtrackerBwUsageByRoleSummary.md) |  | [optional] 
**bwusage_top_regions** | [**List[StatsmonBandwidthtrackerBwUsageByTopRegions]**](StatsmonBandwidthtrackerBwUsageByTopRegions.md) |  | [optional] 
**min_time** | [**GoogleProtobufTimestamp**](GoogleProtobufTimestamp.md) |  | [optional] 
**percent_changed** | **float** |  | [optional] 
**provider_count** | **int** |  | [optional] 
**region_count** | **int** |  | [optional] 
**site_count** | **int** |  | [optional] 
**usage_kbps** | **float** |  | [optional] 

## Example

```python
from graphiant_sdk.models.statsmon_bandwidthtracker_bw_usage_by_enterprise_summary import StatsmonBandwidthtrackerBwUsageByEnterpriseSummary

# TODO update the JSON string below
json = "{}"
# create an instance of StatsmonBandwidthtrackerBwUsageByEnterpriseSummary from a JSON string
statsmon_bandwidthtracker_bw_usage_by_enterprise_summary_instance = StatsmonBandwidthtrackerBwUsageByEnterpriseSummary.from_json(json)
# print the JSON string representation of the object
print(StatsmonBandwidthtrackerBwUsageByEnterpriseSummary.to_json())

# convert the object into a dict
statsmon_bandwidthtracker_bw_usage_by_enterprise_summary_dict = statsmon_bandwidthtracker_bw_usage_by_enterprise_summary_instance.to_dict()
# create an instance of StatsmonBandwidthtrackerBwUsageByEnterpriseSummary from a dict
statsmon_bandwidthtracker_bw_usage_by_enterprise_summary_from_dict = StatsmonBandwidthtrackerBwUsageByEnterpriseSummary.from_dict(statsmon_bandwidthtracker_bw_usage_by_enterprise_summary_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


