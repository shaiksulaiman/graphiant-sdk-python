# StatsmonBandwidthtrackerBwUsageByTopProviders


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**capacity_kbps** | **float** |  | [optional] 
**provider_id** | **int** |  | [optional] 
**provider_name** | **str** |  | [optional] 
**usage_kbps** | **float** |  | [optional] 

## Example

```python
from graphiant_sdk.models.statsmon_bandwidthtracker_bw_usage_by_top_providers import StatsmonBandwidthtrackerBwUsageByTopProviders

# TODO update the JSON string below
json = "{}"
# create an instance of StatsmonBandwidthtrackerBwUsageByTopProviders from a JSON string
statsmon_bandwidthtracker_bw_usage_by_top_providers_instance = StatsmonBandwidthtrackerBwUsageByTopProviders.from_json(json)
# print the JSON string representation of the object
print(StatsmonBandwidthtrackerBwUsageByTopProviders.to_json())

# convert the object into a dict
statsmon_bandwidthtracker_bw_usage_by_top_providers_dict = statsmon_bandwidthtracker_bw_usage_by_top_providers_instance.to_dict()
# create an instance of StatsmonBandwidthtrackerBwUsageByTopProviders from a dict
statsmon_bandwidthtracker_bw_usage_by_top_providers_from_dict = StatsmonBandwidthtrackerBwUsageByTopProviders.from_dict(statsmon_bandwidthtracker_bw_usage_by_top_providers_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


