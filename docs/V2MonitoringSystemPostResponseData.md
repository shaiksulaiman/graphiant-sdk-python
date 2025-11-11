# V2MonitoringSystemPostResponseData


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**samples** | [**List[StatsmonV2StatsSample]**](StatsmonV2StatsSample.md) |  | [optional] 
**selector** | [**StatsmonV2SystemStatsSelector**](StatsmonV2SystemStatsSelector.md) |  | [optional] 

## Example

```python
from graphiant_sdk.models.v2_monitoring_system_post_response_data import V2MonitoringSystemPostResponseData

# TODO update the JSON string below
json = "{}"
# create an instance of V2MonitoringSystemPostResponseData from a JSON string
v2_monitoring_system_post_response_data_instance = V2MonitoringSystemPostResponseData.from_json(json)
# print the JSON string representation of the object
print(V2MonitoringSystemPostResponseData.to_json())

# convert the object into a dict
v2_monitoring_system_post_response_data_dict = v2_monitoring_system_post_response_data_instance.to_dict()
# create an instance of V2MonitoringSystemPostResponseData from a dict
v2_monitoring_system_post_response_data_from_dict = V2MonitoringSystemPostResponseData.from_dict(v2_monitoring_system_post_response_data_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


