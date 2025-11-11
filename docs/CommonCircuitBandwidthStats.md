# CommonCircuitBandwidthStats


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**dl_bw_kbps** | **float** |  | [optional] 
**ts** | [**GoogleProtobufTimestamp**](GoogleProtobufTimestamp.md) |  | [optional] 
**ul_bw_kbps** | **float** |  | [optional] 

## Example

```python
from graphiant_sdk.models.common_circuit_bandwidth_stats import CommonCircuitBandwidthStats

# TODO update the JSON string below
json = "{}"
# create an instance of CommonCircuitBandwidthStats from a JSON string
common_circuit_bandwidth_stats_instance = CommonCircuitBandwidthStats.from_json(json)
# print the JSON string representation of the object
print(CommonCircuitBandwidthStats.to_json())

# convert the object into a dict
common_circuit_bandwidth_stats_dict = common_circuit_bandwidth_stats_instance.to_dict()
# create an instance of CommonCircuitBandwidthStats from a dict
common_circuit_bandwidth_stats_from_dict = CommonCircuitBandwidthStats.from_dict(common_circuit_bandwidth_stats_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


