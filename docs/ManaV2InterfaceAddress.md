# ManaV2InterfaceAddress


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**address** | **str** |  | [optional] 
**dhcp_client** | **bool** |  | [optional] 
**dhcp_relay** | [**ManaV2DhcpRelay**](ManaV2DhcpRelay.md) |  | [optional] 
**dhcp_server** | **bool** |  | [optional] 
**origin** | **str** |  | [optional] 
**vrrp_group** | [**ManaV2VrrpGroup**](ManaV2VrrpGroup.md) |  | [optional] 

## Example

```python
from graphiant_sdk.models.mana_v2_interface_address import ManaV2InterfaceAddress

# TODO update the JSON string below
json = "{}"
# create an instance of ManaV2InterfaceAddress from a JSON string
mana_v2_interface_address_instance = ManaV2InterfaceAddress.from_json(json)
# print the JSON string representation of the object
print(ManaV2InterfaceAddress.to_json())

# convert the object into a dict
mana_v2_interface_address_dict = mana_v2_interface_address_instance.to_dict()
# create an instance of ManaV2InterfaceAddress from a dict
mana_v2_interface_address_from_dict = ManaV2InterfaceAddress.from_dict(mana_v2_interface_address_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


