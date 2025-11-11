# ManaV2DhcpStaticLease


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**hostname** | **str** |  | [optional] 
**id** | **int** |  | [optional] 
**ip_address** | **str** |  | [optional] 
**mac_address** | **str** |  | [optional] 
**vrf** | **str** |  | [optional] 

## Example

```python
from graphiant_sdk.models.mana_v2_dhcp_static_lease import ManaV2DhcpStaticLease

# TODO update the JSON string below
json = "{}"
# create an instance of ManaV2DhcpStaticLease from a JSON string
mana_v2_dhcp_static_lease_instance = ManaV2DhcpStaticLease.from_json(json)
# print the JSON string representation of the object
print(ManaV2DhcpStaticLease.to_json())

# convert the object into a dict
mana_v2_dhcp_static_lease_dict = mana_v2_dhcp_static_lease_instance.to_dict()
# create an instance of ManaV2DhcpStaticLease from a dict
mana_v2_dhcp_static_lease_from_dict = ManaV2DhcpStaticLease.from_dict(mana_v2_dhcp_static_lease_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


