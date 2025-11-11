# ManaV2InterfaceDhcpConfig


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**dhcp_client** | **bool** |  | [optional] 
**dhcp_relay** | [**ManaV2DhcpRelayConfig**](ManaV2DhcpRelayConfig.md) |  | [optional] 

## Example

```python
from graphiant_sdk.models.mana_v2_interface_dhcp_config import ManaV2InterfaceDhcpConfig

# TODO update the JSON string below
json = "{}"
# create an instance of ManaV2InterfaceDhcpConfig from a JSON string
mana_v2_interface_dhcp_config_instance = ManaV2InterfaceDhcpConfig.from_json(json)
# print the JSON string representation of the object
print(ManaV2InterfaceDhcpConfig.to_json())

# convert the object into a dict
mana_v2_interface_dhcp_config_dict = mana_v2_interface_dhcp_config_instance.to_dict()
# create an instance of ManaV2InterfaceDhcpConfig from a dict
mana_v2_interface_dhcp_config_from_dict = ManaV2InterfaceDhcpConfig.from_dict(mana_v2_interface_dhcp_config_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


