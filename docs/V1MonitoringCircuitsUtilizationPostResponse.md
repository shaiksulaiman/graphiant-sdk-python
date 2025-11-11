# V1MonitoringCircuitsUtilizationPostResponse


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**circuit_utilization** | [**List[StatsmonCircuitUtilization]**](StatsmonCircuitUtilization.md) |  | [optional] 

## Example

```python
from graphiant_sdk.models.v1_monitoring_circuits_utilization_post_response import V1MonitoringCircuitsUtilizationPostResponse

# TODO update the JSON string below
json = "{}"
# create an instance of V1MonitoringCircuitsUtilizationPostResponse from a JSON string
v1_monitoring_circuits_utilization_post_response_instance = V1MonitoringCircuitsUtilizationPostResponse.from_json(json)
# print the JSON string representation of the object
print(V1MonitoringCircuitsUtilizationPostResponse.to_json())

# convert the object into a dict
v1_monitoring_circuits_utilization_post_response_dict = v1_monitoring_circuits_utilization_post_response_instance.to_dict()
# create an instance of V1MonitoringCircuitsUtilizationPostResponse from a dict
v1_monitoring_circuits_utilization_post_response_from_dict = V1MonitoringCircuitsUtilizationPostResponse.from_dict(v1_monitoring_circuits_utilization_post_response_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


