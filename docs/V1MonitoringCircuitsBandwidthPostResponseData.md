# V1MonitoringCircuitsBandwidthPostResponseData


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**selector** | [**CommonCircuitBandwidthStatsSelector**](CommonCircuitBandwidthStatsSelector.md) |  | [optional] 
**stats** | [**List[CommonCircuitBandwidthStats]**](CommonCircuitBandwidthStats.md) |  | [optional] 

## Example

```python
from graphiant_sdk.models.v1_monitoring_circuits_bandwidth_post_response_data import V1MonitoringCircuitsBandwidthPostResponseData

# TODO update the JSON string below
json = "{}"
# create an instance of V1MonitoringCircuitsBandwidthPostResponseData from a JSON string
v1_monitoring_circuits_bandwidth_post_response_data_instance = V1MonitoringCircuitsBandwidthPostResponseData.from_json(json)
# print the JSON string representation of the object
print(V1MonitoringCircuitsBandwidthPostResponseData.to_json())

# convert the object into a dict
v1_monitoring_circuits_bandwidth_post_response_data_dict = v1_monitoring_circuits_bandwidth_post_response_data_instance.to_dict()
# create an instance of V1MonitoringCircuitsBandwidthPostResponseData from a dict
v1_monitoring_circuits_bandwidth_post_response_data_from_dict = V1MonitoringCircuitsBandwidthPostResponseData.from_dict(v1_monitoring_circuits_bandwidth_post_response_data_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


