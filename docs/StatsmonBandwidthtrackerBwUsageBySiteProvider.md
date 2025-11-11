# StatsmonBandwidthtrackerBwUsageBySiteProvider


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**provider_id** | **int** |  | [optional] 
**provider_name** | **str** |  | [optional] 
**usage_kbps** | **float** |  | [optional] 

## Example

```python
from graphiant_sdk.models.statsmon_bandwidthtracker_bw_usage_by_site_provider import StatsmonBandwidthtrackerBwUsageBySiteProvider

# TODO update the JSON string below
json = "{}"
# create an instance of StatsmonBandwidthtrackerBwUsageBySiteProvider from a JSON string
statsmon_bandwidthtracker_bw_usage_by_site_provider_instance = StatsmonBandwidthtrackerBwUsageBySiteProvider.from_json(json)
# print the JSON string representation of the object
print(StatsmonBandwidthtrackerBwUsageBySiteProvider.to_json())

# convert the object into a dict
statsmon_bandwidthtracker_bw_usage_by_site_provider_dict = statsmon_bandwidthtracker_bw_usage_by_site_provider_instance.to_dict()
# create an instance of StatsmonBandwidthtrackerBwUsageBySiteProvider from a dict
statsmon_bandwidthtracker_bw_usage_by_site_provider_from_dict = StatsmonBandwidthtrackerBwUsageBySiteProvider.from_dict(statsmon_bandwidthtracker_bw_usage_by_site_provider_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


