# ManaV2CoreInterfaceConfig


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**admin_status** | **bool** |  | [optional] 
**alias** | **str** |  | [optional] 
**description** | **str** |  | [optional] 
**duplex** | **str** |  | [optional] 
**ipv4** | [**ManaV2InterfaceIpConfig**](ManaV2InterfaceIpConfig.md) |  | [optional] 
**ipv6** | [**ManaV2InterfaceIpConfig**](ManaV2InterfaceIpConfig.md) |  | [optional] 
**max_transmission_unit** | **int** |  | [optional] 
**mpls_enabled** | **bool** |  | [optional] 
**tcp_mss_v4** | **int** |  | [optional] 
**tcp_mss_v6** | **int** |  | [optional] 
**x_talk_filter** | **bool** |  | [optional] 

## Example

```python
from graphiant_sdk.models.mana_v2_core_interface_config import ManaV2CoreInterfaceConfig

# TODO update the JSON string below
json = "{}"
# create an instance of ManaV2CoreInterfaceConfig from a JSON string
mana_v2_core_interface_config_instance = ManaV2CoreInterfaceConfig.from_json(json)
# print the JSON string representation of the object
print(ManaV2CoreInterfaceConfig.to_json())

# convert the object into a dict
mana_v2_core_interface_config_dict = mana_v2_core_interface_config_instance.to_dict()
# create an instance of ManaV2CoreInterfaceConfig from a dict
mana_v2_core_interface_config_from_dict = ManaV2CoreInterfaceConfig.from_dict(mana_v2_core_interface_config_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


