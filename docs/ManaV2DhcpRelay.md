# ManaV2DhcpRelay


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**dhcpv4_relays** | **List[str]** |  | [optional] 
**dhcpv6_relays** | **List[str]** |  | [optional] 
**id** | **int** |  | [optional] 

## Example

```python
from graphiant_sdk.models.mana_v2_dhcp_relay import ManaV2DhcpRelay

# TODO update the JSON string below
json = "{}"
# create an instance of ManaV2DhcpRelay from a JSON string
mana_v2_dhcp_relay_instance = ManaV2DhcpRelay.from_json(json)
# print the JSON string representation of the object
print(ManaV2DhcpRelay.to_json())

# convert the object into a dict
mana_v2_dhcp_relay_dict = mana_v2_dhcp_relay_instance.to_dict()
# create an instance of ManaV2DhcpRelay from a dict
mana_v2_dhcp_relay_from_dict = ManaV2DhcpRelay.from_dict(mana_v2_dhcp_relay_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


