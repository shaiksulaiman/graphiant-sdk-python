# ManaV2DhcpLease


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**ends_at** | [**GoogleProtobufTimestamp**](GoogleProtobufTimestamp.md) |  | [optional] 
**id** | **int** |  | [optional] 
**ip_address** | **str** |  | [optional] 
**mac_address** | **str** |  | [optional] 
**vrf** | **str** |  | [optional] 

## Example

```python
from graphiant_sdk.models.mana_v2_dhcp_lease import ManaV2DhcpLease

# TODO update the JSON string below
json = "{}"
# create an instance of ManaV2DhcpLease from a JSON string
mana_v2_dhcp_lease_instance = ManaV2DhcpLease.from_json(json)
# print the JSON string representation of the object
print(ManaV2DhcpLease.to_json())

# convert the object into a dict
mana_v2_dhcp_lease_dict = mana_v2_dhcp_lease_instance.to_dict()
# create an instance of ManaV2DhcpLease from a dict
mana_v2_dhcp_lease_from_dict = ManaV2DhcpLease.from_dict(mana_v2_dhcp_lease_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


