# ManaV2BgpNeighborConfig


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**address_families** | [**Dict[str, ManaV2NullableBgpNeighborAddressFamilyConfig]**](ManaV2NullableBgpNeighborAddressFamilyConfig.md) |  | [optional] 
**allow_as_in** | [**ManaV2NullableAllowAsIn**](ManaV2NullableAllowAsIn.md) |  | [optional] 
**as_override** | **bool** |  | [optional] 
**bfd** | [**ManaV2NullableBfdInstanceConfig**](ManaV2NullableBfdInstanceConfig.md) |  | [optional] 
**default_originate** | **str** |  | [optional] 
**ebgp_multihop_ttl** | [**ManaV2NullableEbgpConfig**](ManaV2NullableEbgpConfig.md) |  | [optional] 
**enabled** | **bool** |  | [optional] 
**hold_timer** | **int** |  | [optional] 
**hold_timer_value** | [**ManaV2NullableHoldTimer**](ManaV2NullableHoldTimer.md) |  | [optional] 
**keepalive_timer** | **int** |  | [optional] 
**keepalive_timer_value** | [**ManaV2NullableKeepAliveTimer**](ManaV2NullableKeepAliveTimer.md) |  | [optional] 
**local_address** | **str** |  | [optional] 
**local_interface** | [**ManaV2NullableInterfaceName**](ManaV2NullableInterfaceName.md) |  | [optional] 
**max_prefix_value** | [**ManaV2NullableMaxPrefix**](ManaV2NullableMaxPrefix.md) |  | [optional] 
**md5_password** | [**ManaV2NullableMd5Password**](ManaV2NullableMd5Password.md) |  | [optional] 
**peer_asn** | **int** |  | [optional] 
**remote_address** | **str** |  | [optional] 
**remove_private_as** | **bool** |  | [optional] 
**send_community** | **bool** |  | [optional] 

## Example

```python
from graphiant_sdk.models.mana_v2_bgp_neighbor_config import ManaV2BgpNeighborConfig

# TODO update the JSON string below
json = "{}"
# create an instance of ManaV2BgpNeighborConfig from a JSON string
mana_v2_bgp_neighbor_config_instance = ManaV2BgpNeighborConfig.from_json(json)
# print the JSON string representation of the object
print(ManaV2BgpNeighborConfig.to_json())

# convert the object into a dict
mana_v2_bgp_neighbor_config_dict = mana_v2_bgp_neighbor_config_instance.to_dict()
# create an instance of ManaV2BgpNeighborConfig from a dict
mana_v2_bgp_neighbor_config_from_dict = ManaV2BgpNeighborConfig.from_dict(mana_v2_bgp_neighbor_config_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


