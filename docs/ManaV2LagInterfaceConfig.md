# ManaV2LagInterfaceConfig


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**admin_status** | **bool** |  | [optional] 
**alias** | **str** |  | [optional] 
**description** | **str** |  | [optional] 
**ipv4** | [**ManaV2InterfaceIpConfig**](ManaV2InterfaceIpConfig.md) |  | [optional] 
**ipv6** | [**ManaV2InterfaceIpConfig**](ManaV2InterfaceIpConfig.md) |  | [optional] 
**lacp** | [**ManaV2LacpConfig**](ManaV2LacpConfig.md) |  | [optional] 
**lag_members** | [**Dict[str, ManaV2NullableLagMemberInterface]**](ManaV2NullableLagMemberInterface.md) |  | [optional] 
**minimum_members** | **int** |  | [optional] 
**mtu** | **int** |  | [optional] 
**segment** | **str** |  | [optional] 
**subinterfaces** | [**Dict[str, ManaV2NullableInterfaceLagvlanConfig]**](ManaV2NullableInterfaceLagvlanConfig.md) |  | [optional] 

## Example

```python
from graphiant_sdk.models.mana_v2_lag_interface_config import ManaV2LagInterfaceConfig

# TODO update the JSON string below
json = "{}"
# create an instance of ManaV2LagInterfaceConfig from a JSON string
mana_v2_lag_interface_config_instance = ManaV2LagInterfaceConfig.from_json(json)
# print the JSON string representation of the object
print(ManaV2LagInterfaceConfig.to_json())

# convert the object into a dict
mana_v2_lag_interface_config_dict = mana_v2_lag_interface_config_instance.to_dict()
# create an instance of ManaV2LagInterfaceConfig from a dict
mana_v2_lag_interface_config_from_dict = ManaV2LagInterfaceConfig.from_dict(mana_v2_lag_interface_config_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


