# ManaV2BfdNeighbor


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**desired_minimum_tx_interval** | **int** |  | [optional] 
**if_index** | **int** |  | [optional] 
**interface** | **str** |  | [optional] 
**last_updated** | [**GoogleProtobufTimestamp**](GoogleProtobufTimestamp.md) |  | [optional] 
**local_diag** | **str** |  | [optional] 
**peer_address** | **str** |  | [optional] 
**remote_diag** | **str** |  | [optional] 
**required_minimum_rx_interval** | **int** |  | [optional] 
**segment_name** | **str** |  | [optional] 
**source_address** | **str** |  | [optional] 
**state** | **str** |  | [optional] 
**time_in_state** | [**GoogleProtobufDuration**](GoogleProtobufDuration.md) |  | [optional] 
**up** | **bool** |  | [optional] 

## Example

```python
from graphiant_sdk.models.mana_v2_bfd_neighbor import ManaV2BfdNeighbor

# TODO update the JSON string below
json = "{}"
# create an instance of ManaV2BfdNeighbor from a JSON string
mana_v2_bfd_neighbor_instance = ManaV2BfdNeighbor.from_json(json)
# print the JSON string representation of the object
print(ManaV2BfdNeighbor.to_json())

# convert the object into a dict
mana_v2_bfd_neighbor_dict = mana_v2_bfd_neighbor_instance.to_dict()
# create an instance of ManaV2BfdNeighbor from a dict
mana_v2_bfd_neighbor_from_dict = ManaV2BfdNeighbor.from_dict(mana_v2_bfd_neighbor_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


