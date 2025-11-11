# V2MonitoringTwampPostResponseData


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**samples** | [**List[StatsmonV2StatsSample]**](StatsmonV2StatsSample.md) |  | [optional] 
**selector** | [**StatsmonV2TwampStatsSelector**](StatsmonV2TwampStatsSelector.md) |  | [optional] 

## Example

```python
from graphiant_sdk.models.v2_monitoring_twamp_post_response_data import V2MonitoringTwampPostResponseData

# TODO update the JSON string below
json = "{}"
# create an instance of V2MonitoringTwampPostResponseData from a JSON string
v2_monitoring_twamp_post_response_data_instance = V2MonitoringTwampPostResponseData.from_json(json)
# print the JSON string representation of the object
print(V2MonitoringTwampPostResponseData.to_json())

# convert the object into a dict
v2_monitoring_twamp_post_response_data_dict = v2_monitoring_twamp_post_response_data_instance.to_dict()
# create an instance of V2MonitoringTwampPostResponseData from a dict
v2_monitoring_twamp_post_response_data_from_dict = V2MonitoringTwampPostResponseData.from_dict(v2_monitoring_twamp_post_response_data_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


