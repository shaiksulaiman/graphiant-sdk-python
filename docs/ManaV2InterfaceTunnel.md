# ManaV2InterfaceTunnel


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**anti_replay_w_size** | **int** |  | [optional] 
**established_time** | [**GoogleProtobufTimestamp**](GoogleProtobufTimestamp.md) |  | [optional] 
**local_circuit** | **str** |  | [optional] 
**local_interface** | [**ManaV2Interface**](ManaV2Interface.md) |  | [optional] 
**local_port** | **int** |  | [optional] 
**local_spi** | **int** |  | [optional] 
**negotiated_algorithms** | **str** |  | [optional] 
**oper_state** | **bool** |  | [optional] 
**peer_address** | **str** |  | [optional] 
**protocol** | **str** |  | [optional] 
**rekey_time** | [**GoogleProtobufTimestamp**](GoogleProtobufTimestamp.md) |  | [optional] 
**remote_port** | **int** |  | [optional] 
**remote_spi** | **int** |  | [optional] 
**session_id** | **int** |  | [optional] 
**source_address** | **str** |  | [optional] 
**tunnel_interface** | [**ManaV2Interface**](ManaV2Interface.md) |  | [optional] 

## Example

```python
from graphiant_sdk.models.mana_v2_interface_tunnel import ManaV2InterfaceTunnel

# TODO update the JSON string below
json = "{}"
# create an instance of ManaV2InterfaceTunnel from a JSON string
mana_v2_interface_tunnel_instance = ManaV2InterfaceTunnel.from_json(json)
# print the JSON string representation of the object
print(ManaV2InterfaceTunnel.to_json())

# convert the object into a dict
mana_v2_interface_tunnel_dict = mana_v2_interface_tunnel_instance.to_dict()
# create an instance of ManaV2InterfaceTunnel from a dict
mana_v2_interface_tunnel_from_dict = ManaV2InterfaceTunnel.from_dict(mana_v2_interface_tunnel_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


