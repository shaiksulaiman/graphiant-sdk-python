# ManaV2NullableDhcpSubnetConfig


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**subnet** | [**ManaV2DhcpSubnetConfig**](ManaV2DhcpSubnetConfig.md) |  | [optional] 

## Example

```python
from graphiant_sdk.models.mana_v2_nullable_dhcp_subnet_config import ManaV2NullableDhcpSubnetConfig

# TODO update the JSON string below
json = "{}"
# create an instance of ManaV2NullableDhcpSubnetConfig from a JSON string
mana_v2_nullable_dhcp_subnet_config_instance = ManaV2NullableDhcpSubnetConfig.from_json(json)
# print the JSON string representation of the object
print(ManaV2NullableDhcpSubnetConfig.to_json())

# convert the object into a dict
mana_v2_nullable_dhcp_subnet_config_dict = mana_v2_nullable_dhcp_subnet_config_instance.to_dict()
# create an instance of ManaV2NullableDhcpSubnetConfig from a dict
mana_v2_nullable_dhcp_subnet_config_from_dict = ManaV2NullableDhcpSubnetConfig.from_dict(mana_v2_nullable_dhcp_subnet_config_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


