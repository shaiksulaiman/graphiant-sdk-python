# ManaV2Dns


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**cloudflare_servers** | [**List[ManaV2DnsipAddress]**](ManaV2DnsipAddress.md) |  | [optional] 
**dynamic_servers** | [**List[ManaV2DnsipAddress]**](ManaV2DnsipAddress.md) |  | [optional] 
**dynamic_servers_v2** | [**ManaV2DynamicDnsServers**](ManaV2DynamicDnsServers.md) |  | [optional] 
**mode** | **str** |  | [optional] 
**static_servers** | [**List[ManaV2DnsipAddress]**](ManaV2DnsipAddress.md) |  | [optional] 
**static_servers_v2** | [**ManaV2StaticDnsServers**](ManaV2StaticDnsServers.md) |  | [optional] 

## Example

```python
from graphiant_sdk.models.mana_v2_dns import ManaV2Dns

# TODO update the JSON string below
json = "{}"
# create an instance of ManaV2Dns from a JSON string
mana_v2_dns_instance = ManaV2Dns.from_json(json)
# print the JSON string representation of the object
print(ManaV2Dns.to_json())

# convert the object into a dict
mana_v2_dns_dict = mana_v2_dns_instance.to_dict()
# create an instance of ManaV2Dns from a dict
mana_v2_dns_from_dict = ManaV2Dns.from_dict(mana_v2_dns_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


