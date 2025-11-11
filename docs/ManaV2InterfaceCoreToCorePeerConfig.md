# ManaV2InterfaceCoreToCorePeerConfig


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**cost** | [**ManaV2CoreLinkCost**](ManaV2CoreLinkCost.md) |  | [optional] 
**ospf_cost** | [**ManaV2CoreLinkCost**](ManaV2CoreLinkCost.md) |  | [optional] 
**peer_hostname** | **str** |  | [optional] 
**type** | **str** |  | [optional] 

## Example

```python
from graphiant_sdk.models.mana_v2_interface_core_to_core_peer_config import ManaV2InterfaceCoreToCorePeerConfig

# TODO update the JSON string below
json = "{}"
# create an instance of ManaV2InterfaceCoreToCorePeerConfig from a JSON string
mana_v2_interface_core_to_core_peer_config_instance = ManaV2InterfaceCoreToCorePeerConfig.from_json(json)
# print the JSON string representation of the object
print(ManaV2InterfaceCoreToCorePeerConfig.to_json())

# convert the object into a dict
mana_v2_interface_core_to_core_peer_config_dict = mana_v2_interface_core_to_core_peer_config_instance.to_dict()
# create an instance of ManaV2InterfaceCoreToCorePeerConfig from a dict
mana_v2_interface_core_to_core_peer_config_from_dict = ManaV2InterfaceCoreToCorePeerConfig.from_dict(mana_v2_interface_core_to_core_peer_config_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


