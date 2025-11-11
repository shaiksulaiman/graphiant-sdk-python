# V2MonitoringBgpPostResponseData


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**samples** | [**List[StatsmonV2StatsSample]**](StatsmonV2StatsSample.md) |  | [optional] 
**selector** | [**StatsmonV2BgpStatsSelector**](StatsmonV2BgpStatsSelector.md) |  | [optional] 

## Example

```python
from graphiant_sdk.models.v2_monitoring_bgp_post_response_data import V2MonitoringBgpPostResponseData

# TODO update the JSON string below
json = "{}"
# create an instance of V2MonitoringBgpPostResponseData from a JSON string
v2_monitoring_bgp_post_response_data_instance = V2MonitoringBgpPostResponseData.from_json(json)
# print the JSON string representation of the object
print(V2MonitoringBgpPostResponseData.to_json())

# convert the object into a dict
v2_monitoring_bgp_post_response_data_dict = v2_monitoring_bgp_post_response_data_instance.to_dict()
# create an instance of V2MonitoringBgpPostResponseData from a dict
v2_monitoring_bgp_post_response_data_from_dict = V2MonitoringBgpPostResponseData.from_dict(v2_monitoring_bgp_post_response_data_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


