# V2MonitoringCircuitsUtilizationPostResponseData


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**config_link_up_speed_mbps** | **int** |  | [optional] 
**queue_utilization** | [**List[StatsmonV2QueueUtilization]**](StatsmonV2QueueUtilization.md) |  | [optional] 
**selector** | [**StatsmonV2CircuitUtilizationSelector**](StatsmonV2CircuitUtilizationSelector.md) |  | [optional] 

## Example

```python
from graphiant_sdk.models.v2_monitoring_circuits_utilization_post_response_data import V2MonitoringCircuitsUtilizationPostResponseData

# TODO update the JSON string below
json = "{}"
# create an instance of V2MonitoringCircuitsUtilizationPostResponseData from a JSON string
v2_monitoring_circuits_utilization_post_response_data_instance = V2MonitoringCircuitsUtilizationPostResponseData.from_json(json)
# print the JSON string representation of the object
print(V2MonitoringCircuitsUtilizationPostResponseData.to_json())

# convert the object into a dict
v2_monitoring_circuits_utilization_post_response_data_dict = v2_monitoring_circuits_utilization_post_response_data_instance.to_dict()
# create an instance of V2MonitoringCircuitsUtilizationPostResponseData from a dict
v2_monitoring_circuits_utilization_post_response_data_from_dict = V2MonitoringCircuitsUtilizationPostResponseData.from_dict(v2_monitoring_circuits_utilization_post_response_data_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


