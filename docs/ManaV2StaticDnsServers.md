# ManaV2StaticDnsServers


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**primary_ipv4_server** | [**ManaV2DnsipAddress**](ManaV2DnsipAddress.md) |  | [optional] 
**primary_ipv6_server** | [**ManaV2DnsipAddress**](ManaV2DnsipAddress.md) |  | [optional] 
**secondary_ipv4_server** | [**ManaV2DnsipAddress**](ManaV2DnsipAddress.md) |  | [optional] 
**secondary_ipv6_server** | [**ManaV2DnsipAddress**](ManaV2DnsipAddress.md) |  | [optional] 

## Example

```python
from graphiant_sdk.models.mana_v2_static_dns_servers import ManaV2StaticDnsServers

# TODO update the JSON string below
json = "{}"
# create an instance of ManaV2StaticDnsServers from a JSON string
mana_v2_static_dns_servers_instance = ManaV2StaticDnsServers.from_json(json)
# print the JSON string representation of the object
print(ManaV2StaticDnsServers.to_json())

# convert the object into a dict
mana_v2_static_dns_servers_dict = mana_v2_static_dns_servers_instance.to_dict()
# create an instance of ManaV2StaticDnsServers from a dict
mana_v2_static_dns_servers_from_dict = ManaV2StaticDnsServers.from_dict(mana_v2_static_dns_servers_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


