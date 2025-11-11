# ManaV2BgpNeighborAddressFamily


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**address_family** | **str** |  | [optional] 
**id** | **int** |  | [optional] 
**inbound_policy** | **str** |  | [optional] 
**outbound_policy** | **str** |  | [optional] 

## Example

```python
from graphiant_sdk.models.mana_v2_bgp_neighbor_address_family import ManaV2BgpNeighborAddressFamily

# TODO update the JSON string below
json = "{}"
# create an instance of ManaV2BgpNeighborAddressFamily from a JSON string
mana_v2_bgp_neighbor_address_family_instance = ManaV2BgpNeighborAddressFamily.from_json(json)
# print the JSON string representation of the object
print(ManaV2BgpNeighborAddressFamily.to_json())

# convert the object into a dict
mana_v2_bgp_neighbor_address_family_dict = mana_v2_bgp_neighbor_address_family_instance.to_dict()
# create an instance of ManaV2BgpNeighborAddressFamily from a dict
mana_v2_bgp_neighbor_address_family_from_dict = ManaV2BgpNeighborAddressFamily.from_dict(mana_v2_bgp_neighbor_address_family_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


