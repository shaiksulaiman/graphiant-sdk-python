# ManaV2NullableIPsecTunnelConfig


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**site_to_site_vpn** | [**ManaV2IPsecTunnel**](ManaV2IPsecTunnel.md) |  | [optional] 

## Example

```python
from graphiant_sdk.models.mana_v2_nullable_i_psec_tunnel_config import ManaV2NullableIPsecTunnelConfig

# TODO update the JSON string below
json = "{}"
# create an instance of ManaV2NullableIPsecTunnelConfig from a JSON string
mana_v2_nullable_i_psec_tunnel_config_instance = ManaV2NullableIPsecTunnelConfig.from_json(json)
# print the JSON string representation of the object
print(ManaV2NullableIPsecTunnelConfig.to_json())

# convert the object into a dict
mana_v2_nullable_i_psec_tunnel_config_dict = mana_v2_nullable_i_psec_tunnel_config_instance.to_dict()
# create an instance of ManaV2NullableIPsecTunnelConfig from a dict
mana_v2_nullable_i_psec_tunnel_config_from_dict = ManaV2NullableIPsecTunnelConfig.from_dict(mana_v2_nullable_i_psec_tunnel_config_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


