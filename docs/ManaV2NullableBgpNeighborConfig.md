# ManaV2NullableBgpNeighborConfig


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**neighbor** | [**ManaV2BgpNeighborConfig**](ManaV2BgpNeighborConfig.md) |  | [optional] 

## Example

```python
from graphiant_sdk.models.mana_v2_nullable_bgp_neighbor_config import ManaV2NullableBgpNeighborConfig

# TODO update the JSON string below
json = "{}"
# create an instance of ManaV2NullableBgpNeighborConfig from a JSON string
mana_v2_nullable_bgp_neighbor_config_instance = ManaV2NullableBgpNeighborConfig.from_json(json)
# print the JSON string representation of the object
print(ManaV2NullableBgpNeighborConfig.to_json())

# convert the object into a dict
mana_v2_nullable_bgp_neighbor_config_dict = mana_v2_nullable_bgp_neighbor_config_instance.to_dict()
# create an instance of ManaV2NullableBgpNeighborConfig from a dict
mana_v2_nullable_bgp_neighbor_config_from_dict = ManaV2NullableBgpNeighborConfig.from_dict(mana_v2_nullable_bgp_neighbor_config_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


