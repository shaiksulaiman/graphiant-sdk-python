# ManaV2IPsecBgpRouteConfig


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**address_families** | [**Dict[str, ManaV2NullableBgpNeighborAddressFamilyConfig]**](ManaV2NullableBgpNeighborAddressFamilyConfig.md) |  | [optional] 
**hold_timer** | **int** |  | [optional] 
**keepalive_timer** | **int** |  | [optional] 
**md5_password** | [**ManaV2NullableMd5Password**](ManaV2NullableMd5Password.md) |  | [optional] 
**peer_asn** | **int** |  | [optional] 
**send_community** | **bool** |  | [optional] 

## Example

```python
from graphiant_sdk.models.mana_v2_i_psec_bgp_route_config import ManaV2IPsecBgpRouteConfig

# TODO update the JSON string below
json = "{}"
# create an instance of ManaV2IPsecBgpRouteConfig from a JSON string
mana_v2_i_psec_bgp_route_config_instance = ManaV2IPsecBgpRouteConfig.from_json(json)
# print the JSON string representation of the object
print(ManaV2IPsecBgpRouteConfig.to_json())

# convert the object into a dict
mana_v2_i_psec_bgp_route_config_dict = mana_v2_i_psec_bgp_route_config_instance.to_dict()
# create an instance of ManaV2IPsecBgpRouteConfig from a dict
mana_v2_i_psec_bgp_route_config_from_dict = ManaV2IPsecBgpRouteConfig.from_dict(mana_v2_i_psec_bgp_route_config_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


