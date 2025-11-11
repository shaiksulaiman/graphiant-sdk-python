# ManaV2DnsipAddress


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**circuit_name** | **str** |  | [optional] 
**interface_name** | **str** |  | [optional] 
**ipv4** | **str** |  | [optional] 
**ipv6** | **str** |  | [optional] 
**source** | **str** |  | [optional] 
**stale** | **bool** |  | [optional] 
**type** | **str** |  | [optional] 

## Example

```python
from graphiant_sdk.models.mana_v2_dnsip_address import ManaV2DnsipAddress

# TODO update the JSON string below
json = "{}"
# create an instance of ManaV2DnsipAddress from a JSON string
mana_v2_dnsip_address_instance = ManaV2DnsipAddress.from_json(json)
# print the JSON string representation of the object
print(ManaV2DnsipAddress.to_json())

# convert the object into a dict
mana_v2_dnsip_address_dict = mana_v2_dnsip_address_instance.to_dict()
# create an instance of ManaV2DnsipAddress from a dict
mana_v2_dnsip_address_from_dict = ManaV2DnsipAddress.from_dict(mana_v2_dnsip_address_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


