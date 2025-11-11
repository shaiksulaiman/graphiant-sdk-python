# ManaV2IpsecRoutingConfig


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**bgp** | [**ManaV2IPsecBgpRouteConfig**](ManaV2IPsecBgpRouteConfig.md) |  | [optional] 
**static** | [**ManaV2IPsecStaticRouteConfig**](ManaV2IPsecStaticRouteConfig.md) |  | [optional] 

## Example

```python
from graphiant_sdk.models.mana_v2_ipsec_routing_config import ManaV2IpsecRoutingConfig

# TODO update the JSON string below
json = "{}"
# create an instance of ManaV2IpsecRoutingConfig from a JSON string
mana_v2_ipsec_routing_config_instance = ManaV2IpsecRoutingConfig.from_json(json)
# print the JSON string representation of the object
print(ManaV2IpsecRoutingConfig.to_json())

# convert the object into a dict
mana_v2_ipsec_routing_config_dict = mana_v2_ipsec_routing_config_instance.to_dict()
# create an instance of ManaV2IpsecRoutingConfig from a dict
mana_v2_ipsec_routing_config_from_dict = ManaV2IpsecRoutingConfig.from_dict(mana_v2_ipsec_routing_config_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


