# V2MonitoringSystemGenericPostRequest


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**device_id** | **int** |  | [optional] 
**selectors** | [**List[StatsmonV2GenericSystemStatsSelector]**](StatsmonV2GenericSystemStatsSelector.md) |  | [optional] 
**time_window** | [**StatsmonV2TimeWindow**](StatsmonV2TimeWindow.md) |  | [optional] 

## Example

```python
from graphiant_sdk.models.v2_monitoring_system_generic_post_request import V2MonitoringSystemGenericPostRequest

# TODO update the JSON string below
json = "{}"
# create an instance of V2MonitoringSystemGenericPostRequest from a JSON string
v2_monitoring_system_generic_post_request_instance = V2MonitoringSystemGenericPostRequest.from_json(json)
# print the JSON string representation of the object
print(V2MonitoringSystemGenericPostRequest.to_json())

# convert the object into a dict
v2_monitoring_system_generic_post_request_dict = v2_monitoring_system_generic_post_request_instance.to_dict()
# create an instance of V2MonitoringSystemGenericPostRequest from a dict
v2_monitoring_system_generic_post_request_from_dict = V2MonitoringSystemGenericPostRequest.from_dict(v2_monitoring_system_generic_post_request_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


