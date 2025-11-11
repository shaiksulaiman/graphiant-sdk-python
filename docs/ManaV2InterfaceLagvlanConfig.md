# ManaV2InterfaceLagvlanConfig


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**admin_status** | **bool** |  | [optional] 
**alias** | **str** |  | [optional] 
**description** | **str** |  | [optional] 
**ipv4** | [**ManaV2InterfaceIpConfig**](ManaV2InterfaceIpConfig.md) |  | [optional] 
**ipv6** | [**ManaV2InterfaceIpConfig**](ManaV2InterfaceIpConfig.md) |  | [optional] 
**segment** | **str** |  | [optional] 
**vlan** | **int** |  | [optional] 

## Example

```python
from graphiant_sdk.models.mana_v2_interface_lagvlan_config import ManaV2InterfaceLagvlanConfig

# TODO update the JSON string below
json = "{}"
# create an instance of ManaV2InterfaceLagvlanConfig from a JSON string
mana_v2_interface_lagvlan_config_instance = ManaV2InterfaceLagvlanConfig.from_json(json)
# print the JSON string representation of the object
print(ManaV2InterfaceLagvlanConfig.to_json())

# convert the object into a dict
mana_v2_interface_lagvlan_config_dict = mana_v2_interface_lagvlan_config_instance.to_dict()
# create an instance of ManaV2InterfaceLagvlanConfig from a dict
mana_v2_interface_lagvlan_config_from_dict = ManaV2InterfaceLagvlanConfig.from_dict(mana_v2_interface_lagvlan_config_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


