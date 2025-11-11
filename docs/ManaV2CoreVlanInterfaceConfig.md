# ManaV2CoreVlanInterfaceConfig


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**core_neighbor** | [**ManaV2InterfaceCoreToCorePeerConfig**](ManaV2InterfaceCoreToCorePeerConfig.md) |  | [optional] 
**default** | **object** |  | [optional] 
**gateway_neighbor** | [**ManaV2InterfaceCoreToGatewayPeerConfig**](ManaV2InterfaceCoreToGatewayPeerConfig.md) |  | [optional] 
**interface** | [**ManaV2CoreInterfaceConfig**](ManaV2CoreInterfaceConfig.md) |  | [optional] 
**interface_type** | [**ManaV2interfaceConfigType**](ManaV2interfaceConfigType.md) |  | [optional] 
**vlan_id** | **int** |  | [optional] 
**wan** | [**ManaV2InterfaceWanConfig**](ManaV2InterfaceWanConfig.md) |  | [optional] 

## Example

```python
from graphiant_sdk.models.mana_v2_core_vlan_interface_config import ManaV2CoreVlanInterfaceConfig

# TODO update the JSON string below
json = "{}"
# create an instance of ManaV2CoreVlanInterfaceConfig from a JSON string
mana_v2_core_vlan_interface_config_instance = ManaV2CoreVlanInterfaceConfig.from_json(json)
# print the JSON string representation of the object
print(ManaV2CoreVlanInterfaceConfig.to_json())

# convert the object into a dict
mana_v2_core_vlan_interface_config_dict = mana_v2_core_vlan_interface_config_instance.to_dict()
# create an instance of ManaV2CoreVlanInterfaceConfig from a dict
mana_v2_core_vlan_interface_config_from_dict = ManaV2CoreVlanInterfaceConfig.from_dict(mana_v2_core_vlan_interface_config_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


