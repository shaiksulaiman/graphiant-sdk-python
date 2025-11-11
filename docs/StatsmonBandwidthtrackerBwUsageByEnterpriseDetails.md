# StatsmonBandwidthtrackerBwUsageByEnterpriseDetails


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**bwusage_region** | [**List[StatsmonBandwidthtrackerBwUsageByRegion]**](StatsmonBandwidthtrackerBwUsageByRegion.md) |  | [optional] 
**bwusage_site** | [**List[StatsmonBandwidthtrackerBwUsageBySite]**](StatsmonBandwidthtrackerBwUsageBySite.md) |  | [optional] 
**bwusage_site_gateway** | [**List[StatsmonBandwidthtrackerBwUsageBySite]**](StatsmonBandwidthtrackerBwUsageBySite.md) |  | [optional] 

## Example

```python
from graphiant_sdk.models.statsmon_bandwidthtracker_bw_usage_by_enterprise_details import StatsmonBandwidthtrackerBwUsageByEnterpriseDetails

# TODO update the JSON string below
json = "{}"
# create an instance of StatsmonBandwidthtrackerBwUsageByEnterpriseDetails from a JSON string
statsmon_bandwidthtracker_bw_usage_by_enterprise_details_instance = StatsmonBandwidthtrackerBwUsageByEnterpriseDetails.from_json(json)
# print the JSON string representation of the object
print(StatsmonBandwidthtrackerBwUsageByEnterpriseDetails.to_json())

# convert the object into a dict
statsmon_bandwidthtracker_bw_usage_by_enterprise_details_dict = statsmon_bandwidthtracker_bw_usage_by_enterprise_details_instance.to_dict()
# create an instance of StatsmonBandwidthtrackerBwUsageByEnterpriseDetails from a dict
statsmon_bandwidthtracker_bw_usage_by_enterprise_details_from_dict = StatsmonBandwidthtrackerBwUsageByEnterpriseDetails.from_dict(statsmon_bandwidthtracker_bw_usage_by_enterprise_details_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


