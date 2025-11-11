# StatsmonBandwidthtrackerBwUsageByRoleSummary


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**role_id** | **int** |  | [optional] 
**role_name** | **str** |  | [optional] 
**usage_kbps** | **float** |  | [optional] 

## Example

```python
from graphiant_sdk.models.statsmon_bandwidthtracker_bw_usage_by_role_summary import StatsmonBandwidthtrackerBwUsageByRoleSummary

# TODO update the JSON string below
json = "{}"
# create an instance of StatsmonBandwidthtrackerBwUsageByRoleSummary from a JSON string
statsmon_bandwidthtracker_bw_usage_by_role_summary_instance = StatsmonBandwidthtrackerBwUsageByRoleSummary.from_json(json)
# print the JSON string representation of the object
print(StatsmonBandwidthtrackerBwUsageByRoleSummary.to_json())

# convert the object into a dict
statsmon_bandwidthtracker_bw_usage_by_role_summary_dict = statsmon_bandwidthtracker_bw_usage_by_role_summary_instance.to_dict()
# create an instance of StatsmonBandwidthtrackerBwUsageByRoleSummary from a dict
statsmon_bandwidthtracker_bw_usage_by_role_summary_from_dict = StatsmonBandwidthtrackerBwUsageByRoleSummary.from_dict(statsmon_bandwidthtracker_bw_usage_by_role_summary_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


