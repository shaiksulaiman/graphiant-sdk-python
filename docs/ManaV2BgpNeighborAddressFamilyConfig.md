# ManaV2BgpNeighborAddressFamilyConfig


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**address_family** | **str** |  | [optional] 
**inbound_policy** | [**ManaV2NullablePolicyName**](ManaV2NullablePolicyName.md) |  | [optional] 
**outbound_policy** | [**ManaV2NullablePolicyName**](ManaV2NullablePolicyName.md) |  | [optional] 

## Example

```python
from graphiant_sdk.models.mana_v2_bgp_neighbor_address_family_config import ManaV2BgpNeighborAddressFamilyConfig

# TODO update the JSON string below
json = "{}"
# create an instance of ManaV2BgpNeighborAddressFamilyConfig from a JSON string
mana_v2_bgp_neighbor_address_family_config_instance = ManaV2BgpNeighborAddressFamilyConfig.from_json(json)
# print the JSON string representation of the object
print(ManaV2BgpNeighborAddressFamilyConfig.to_json())

# convert the object into a dict
mana_v2_bgp_neighbor_address_family_config_dict = mana_v2_bgp_neighbor_address_family_config_instance.to_dict()
# create an instance of ManaV2BgpNeighborAddressFamilyConfig from a dict
mana_v2_bgp_neighbor_address_family_config_from_dict = ManaV2BgpNeighborAddressFamilyConfig.from_dict(mana_v2_bgp_neighbor_address_family_config_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


