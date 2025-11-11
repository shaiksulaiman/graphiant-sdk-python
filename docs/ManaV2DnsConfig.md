# ManaV2DnsConfig


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**cloudflare** | **object** |  | [optional] 
**dynamic** | [**ManaV2DNSConfigDynamic**](ManaV2DNSConfigDynamic.md) |  | [optional] 
**static** | [**ManaV2DNSConfigStatic**](ManaV2DNSConfigStatic.md) |  | [optional] 

## Example

```python
from graphiant_sdk.models.mana_v2_dns_config import ManaV2DnsConfig

# TODO update the JSON string below
json = "{}"
# create an instance of ManaV2DnsConfig from a JSON string
mana_v2_dns_config_instance = ManaV2DnsConfig.from_json(json)
# print the JSON string representation of the object
print(ManaV2DnsConfig.to_json())

# convert the object into a dict
mana_v2_dns_config_dict = mana_v2_dns_config_instance.to_dict()
# create an instance of ManaV2DnsConfig from a dict
mana_v2_dns_config_from_dict = ManaV2DnsConfig.from_dict(mana_v2_dns_config_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


