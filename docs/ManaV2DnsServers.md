# ManaV2DnsServers


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**primary** | **str** |  | [optional] 
**secondary** | **str** |  | [optional] 

## Example

```python
from graphiant_sdk.models.mana_v2_dns_servers import ManaV2DnsServers

# TODO update the JSON string below
json = "{}"
# create an instance of ManaV2DnsServers from a JSON string
mana_v2_dns_servers_instance = ManaV2DnsServers.from_json(json)
# print the JSON string representation of the object
print(ManaV2DnsServers.to_json())

# convert the object into a dict
mana_v2_dns_servers_dict = mana_v2_dns_servers_instance.to_dict()
# create an instance of ManaV2DnsServers from a dict
mana_v2_dns_servers_from_dict = ManaV2DnsServers.from_dict(mana_v2_dns_servers_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


