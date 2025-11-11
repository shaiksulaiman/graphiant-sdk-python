# ManaV2DnsipAddresses


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**dynamic_servers** | [**List[ManaV2DnsipAddress]**](ManaV2DnsipAddress.md) |  | [optional] 

## Example

```python
from graphiant_sdk.models.mana_v2_dnsip_addresses import ManaV2DnsipAddresses

# TODO update the JSON string below
json = "{}"
# create an instance of ManaV2DnsipAddresses from a JSON string
mana_v2_dnsip_addresses_instance = ManaV2DnsipAddresses.from_json(json)
# print the JSON string representation of the object
print(ManaV2DnsipAddresses.to_json())

# convert the object into a dict
mana_v2_dnsip_addresses_dict = mana_v2_dnsip_addresses_instance.to_dict()
# create an instance of ManaV2DnsipAddresses from a dict
mana_v2_dnsip_addresses_from_dict = ManaV2DnsipAddresses.from_dict(mana_v2_dnsip_addresses_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


