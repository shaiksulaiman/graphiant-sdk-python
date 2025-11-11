# StatsmonV2EdgeedgeCircuitInfo


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**circuit_carrier** | **str** |  | [optional] 
**circuit_name** | **str** |  | [optional] 
**device_hostname** | **str** |  | [optional] 
**interface_name** | **str** |  | [optional] 
**label** | **str** |  | [optional] 
**last_resort_circuit** | **bool** |  | [optional] 
**quality** | **str** |  | [optional] 
**source_ip** | **str** |  | [optional] 
**source_public_ip** | **str** |  | [optional] 
**uptime** | [**GoogleProtobufTimestamp**](GoogleProtobufTimestamp.md) |  | [optional] 

## Example

```python
from graphiant_sdk.models.statsmon_v2_edgeedge_circuit_info import StatsmonV2EdgeedgeCircuitInfo

# TODO update the JSON string below
json = "{}"
# create an instance of StatsmonV2EdgeedgeCircuitInfo from a JSON string
statsmon_v2_edgeedge_circuit_info_instance = StatsmonV2EdgeedgeCircuitInfo.from_json(json)
# print the JSON string representation of the object
print(StatsmonV2EdgeedgeCircuitInfo.to_json())

# convert the object into a dict
statsmon_v2_edgeedge_circuit_info_dict = statsmon_v2_edgeedge_circuit_info_instance.to_dict()
# create an instance of StatsmonV2EdgeedgeCircuitInfo from a dict
statsmon_v2_edgeedge_circuit_info_from_dict = StatsmonV2EdgeedgeCircuitInfo.from_dict(statsmon_v2_edgeedge_circuit_info_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


