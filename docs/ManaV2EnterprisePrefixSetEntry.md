# ManaV2EnterprisePrefixSetEntry


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**ip_prefix** | **str** |  | [optional] 
**mask_lower** | **int** |  | [optional] 
**mask_upper** | **int** |  | [optional] 
**seq** | **int** |  | [optional] 

## Example

```python
from graphiant_sdk.models.mana_v2_enterprise_prefix_set_entry import ManaV2EnterprisePrefixSetEntry

# TODO update the JSON string below
json = "{}"
# create an instance of ManaV2EnterprisePrefixSetEntry from a JSON string
mana_v2_enterprise_prefix_set_entry_instance = ManaV2EnterprisePrefixSetEntry.from_json(json)
# print the JSON string representation of the object
print(ManaV2EnterprisePrefixSetEntry.to_json())

# convert the object into a dict
mana_v2_enterprise_prefix_set_entry_dict = mana_v2_enterprise_prefix_set_entry_instance.to_dict()
# create an instance of ManaV2EnterprisePrefixSetEntry from a dict
mana_v2_enterprise_prefix_set_entry_from_dict = ManaV2EnterprisePrefixSetEntry.from_dict(mana_v2_enterprise_prefix_set_entry_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


