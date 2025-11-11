# ManaV2DynamicDnsServers


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**circuit** | **str** |  | [optional] 
**servers** | [**Dict[str, ManaV2DnsipAddresses]**](ManaV2DnsipAddresses.md) |  | [optional] 

## Example

```python
from graphiant_sdk.models.mana_v2_dynamic_dns_servers import ManaV2DynamicDnsServers

# TODO update the JSON string below
json = "{}"
# create an instance of ManaV2DynamicDnsServers from a JSON string
mana_v2_dynamic_dns_servers_instance = ManaV2DynamicDnsServers.from_json(json)
# print the JSON string representation of the object
print(ManaV2DynamicDnsServers.to_json())

# convert the object into a dict
mana_v2_dynamic_dns_servers_dict = mana_v2_dynamic_dns_servers_instance.to_dict()
# create an instance of ManaV2DynamicDnsServers from a dict
mana_v2_dynamic_dns_servers_from_dict = ManaV2DynamicDnsServers.from_dict(mana_v2_dynamic_dns_servers_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


