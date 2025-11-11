# ManaV2InterfaceWanConfig


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**gw** | [**ManaV2NullableInterfaceIpConfig**](ManaV2NullableInterfaceIpConfig.md) |  | [optional] 
**type** | **str** |  | [optional] 
**vrf_name** | **str** |  | [optional] 

## Example

```python
from graphiant_sdk.models.mana_v2_interface_wan_config import ManaV2InterfaceWanConfig

# TODO update the JSON string below
json = "{}"
# create an instance of ManaV2InterfaceWanConfig from a JSON string
mana_v2_interface_wan_config_instance = ManaV2InterfaceWanConfig.from_json(json)
# print the JSON string representation of the object
print(ManaV2InterfaceWanConfig.to_json())

# convert the object into a dict
mana_v2_interface_wan_config_dict = mana_v2_interface_wan_config_instance.to_dict()
# create an instance of ManaV2InterfaceWanConfig from a dict
mana_v2_interface_wan_config_from_dict = ManaV2InterfaceWanConfig.from_dict(mana_v2_interface_wan_config_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


