# ManaV2DNSConfigStatic


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**primary_ipv4_v2** | [**ManaV2NullableIPv4Address**](ManaV2NullableIPv4Address.md) |  | [optional] 
**primary_ipv6_v2** | [**ManaV2NullableIPv6Address**](ManaV2NullableIPv6Address.md) |  | [optional] 
**secondary_ipv4_v2** | [**ManaV2NullableIPv4Address**](ManaV2NullableIPv4Address.md) |  | [optional] 
**secondary_ipv6_v2** | [**ManaV2NullableIPv6Address**](ManaV2NullableIPv6Address.md) |  | [optional] 

## Example

```python
from graphiant_sdk.models.mana_v2_dns_config_static import ManaV2DNSConfigStatic

# TODO update the JSON string below
json = "{}"
# create an instance of ManaV2DNSConfigStatic from a JSON string
mana_v2_dns_config_static_instance = ManaV2DNSConfigStatic.from_json(json)
# print the JSON string representation of the object
print(ManaV2DNSConfigStatic.to_json())

# convert the object into a dict
mana_v2_dns_config_static_dict = mana_v2_dns_config_static_instance.to_dict()
# create an instance of ManaV2DNSConfigStatic from a dict
mana_v2_dns_config_static_from_dict = ManaV2DNSConfigStatic.from_dict(mana_v2_dns_config_static_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


