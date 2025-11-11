# V1MonitoringCircuitsSummaryPostRequest


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**device_id** | **int** |  | [optional] 
**time_window** | [**StatsmonTimeWindow**](StatsmonTimeWindow.md) |  | [optional] 

## Example

```python
from graphiant_sdk.models.v1_monitoring_circuits_summary_post_request import V1MonitoringCircuitsSummaryPostRequest

# TODO update the JSON string below
json = "{}"
# create an instance of V1MonitoringCircuitsSummaryPostRequest from a JSON string
v1_monitoring_circuits_summary_post_request_instance = V1MonitoringCircuitsSummaryPostRequest.from_json(json)
# print the JSON string representation of the object
print(V1MonitoringCircuitsSummaryPostRequest.to_json())

# convert the object into a dict
v1_monitoring_circuits_summary_post_request_dict = v1_monitoring_circuits_summary_post_request_instance.to_dict()
# create an instance of V1MonitoringCircuitsSummaryPostRequest from a dict
v1_monitoring_circuits_summary_post_request_from_dict = V1MonitoringCircuitsSummaryPostRequest.from_dict(v1_monitoring_circuits_summary_post_request_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


