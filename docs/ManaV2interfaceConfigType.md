# ManaV2interfaceConfigType


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**core_neighbor** | [**ManaV2InterfaceCoreToCorePeerConfig**](ManaV2InterfaceCoreToCorePeerConfig.md) |  | [optional] 
**core_to_core_tunnel** | **object** |  | [optional] 
**default** | **object** |  | [optional] 
**gateway_neighbor** | [**ManaV2InterfaceCoreToGatewayPeerConfig**](ManaV2InterfaceCoreToGatewayPeerConfig.md) |  | [optional] 
**wan** | [**ManaV2InterfaceWanConfig**](ManaV2InterfaceWanConfig.md) |  | [optional] 
**wan_management** | **object** |  | [optional] 

## Example

```python
from graphiant_sdk.models.mana_v2interface_config_type import ManaV2interfaceConfigType

# TODO update the JSON string below
json = "{}"
# create an instance of ManaV2interfaceConfigType from a JSON string
mana_v2interface_config_type_instance = ManaV2interfaceConfigType.from_json(json)
# print the JSON string representation of the object
print(ManaV2interfaceConfigType.to_json())

# convert the object into a dict
mana_v2interface_config_type_dict = mana_v2interface_config_type_instance.to_dict()
# create an instance of ManaV2interfaceConfigType from a dict
mana_v2interface_config_type_from_dict = ManaV2interfaceConfigType.from_dict(mana_v2interface_config_type_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


