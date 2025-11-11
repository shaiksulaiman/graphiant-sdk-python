# V2MonitoringCircuitsBandwidthPostResponseData


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**carrier** | **str** |  | [optional] 
**device_id** | **int** |  | [optional] 
**dl_bw_kbps_samples** | [**List[StatsmonV2StatsSample]**](StatsmonV2StatsSample.md) |  | [optional] 
**selector** | [**StatsmonV2CircuitBandwidthStatsSelector**](StatsmonV2CircuitBandwidthStatsSelector.md) |  | [optional] 
**ul_bw_kbps_samples** | [**List[StatsmonV2StatsSample]**](StatsmonV2StatsSample.md) |  | [optional] 

## Example

```python
from graphiant_sdk.models.v2_monitoring_circuits_bandwidth_post_response_data import V2MonitoringCircuitsBandwidthPostResponseData

# TODO update the JSON string below
json = "{}"
# create an instance of V2MonitoringCircuitsBandwidthPostResponseData from a JSON string
v2_monitoring_circuits_bandwidth_post_response_data_instance = V2MonitoringCircuitsBandwidthPostResponseData.from_json(json)
# print the JSON string representation of the object
print(V2MonitoringCircuitsBandwidthPostResponseData.to_json())

# convert the object into a dict
v2_monitoring_circuits_bandwidth_post_response_data_dict = v2_monitoring_circuits_bandwidth_post_response_data_instance.to_dict()
# create an instance of V2MonitoringCircuitsBandwidthPostResponseData from a dict
v2_monitoring_circuits_bandwidth_post_response_data_from_dict = V2MonitoringCircuitsBandwidthPostResponseData.from_dict(v2_monitoring_circuits_bandwidth_post_response_data_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


