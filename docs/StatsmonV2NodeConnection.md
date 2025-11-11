# StatsmonV2NodeConnection


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**active** | **bool** |  | [optional] 
**circuit_carrier** | **str** |  | [optional] 
**circuit_name** | **str** |  | [optional] 
**destination_ip** | **str** |  | [optional] 
**hostname** | **str** |  | [optional] 
**last_established_time** | [**GoogleProtobufTimestamp**](GoogleProtobufTimestamp.md) |  | [optional] 
**last_resort** | **bool** |  | [optional] 
**quality** | **str** |  | [optional] 
**source_ip** | **str** |  | [optional] 
**source_public_ip** | **str** |  | [optional] 

## Example

```python
from graphiant_sdk.models.statsmon_v2_node_connection import StatsmonV2NodeConnection

# TODO update the JSON string below
json = "{}"
# create an instance of StatsmonV2NodeConnection from a JSON string
statsmon_v2_node_connection_instance = StatsmonV2NodeConnection.from_json(json)
# print the JSON string representation of the object
print(StatsmonV2NodeConnection.to_json())

# convert the object into a dict
statsmon_v2_node_connection_dict = statsmon_v2_node_connection_instance.to_dict()
# create an instance of StatsmonV2NodeConnection from a dict
statsmon_v2_node_connection_from_dict = StatsmonV2NodeConnection.from_dict(statsmon_v2_node_connection_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


