# ManaV2DNSConfigDynamic


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**circuit_name** | **str** |  | [optional] 
**interface_name** | **str** |  | [optional] 

## Example

```python
from graphiant_sdk.models.mana_v2_dns_config_dynamic import ManaV2DNSConfigDynamic

# TODO update the JSON string below
json = "{}"
# create an instance of ManaV2DNSConfigDynamic from a JSON string
mana_v2_dns_config_dynamic_instance = ManaV2DNSConfigDynamic.from_json(json)
# print the JSON string representation of the object
print(ManaV2DNSConfigDynamic.to_json())

# convert the object into a dict
mana_v2_dns_config_dynamic_dict = mana_v2_dns_config_dynamic_instance.to_dict()
# create an instance of ManaV2DNSConfigDynamic from a dict
mana_v2_dns_config_dynamic_from_dict = ManaV2DNSConfigDynamic.from_dict(mana_v2_dns_config_dynamic_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


