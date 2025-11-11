# V1MonitoringCircuitsUtilizationPostRequest


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**device_id** | **int** |  | [optional] 
**selectors** | [**List[StatsmonCircuitsUtilizationSelector]**](StatsmonCircuitsUtilizationSelector.md) |  | [optional] 
**time_window** | [**StatsmonTimeWindow**](StatsmonTimeWindow.md) |  | [optional] 

## Example

```python
from graphiant_sdk.models.v1_monitoring_circuits_utilization_post_request import V1MonitoringCircuitsUtilizationPostRequest

# TODO update the JSON string below
json = "{}"
# create an instance of V1MonitoringCircuitsUtilizationPostRequest from a JSON string
v1_monitoring_circuits_utilization_post_request_instance = V1MonitoringCircuitsUtilizationPostRequest.from_json(json)
# print the JSON string representation of the object
print(V1MonitoringCircuitsUtilizationPostRequest.to_json())

# convert the object into a dict
v1_monitoring_circuits_utilization_post_request_dict = v1_monitoring_circuits_utilization_post_request_instance.to_dict()
# create an instance of V1MonitoringCircuitsUtilizationPostRequest from a dict
v1_monitoring_circuits_utilization_post_request_from_dict = V1MonitoringCircuitsUtilizationPostRequest.from_dict(v1_monitoring_circuits_utilization_post_request_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


