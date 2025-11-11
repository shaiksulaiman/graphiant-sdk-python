# ManaV2PrefixSetConfigNullableEntryEntry


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**ip_prefix** | **str** |  | [optional] 
**mask_lower** | **int** |  | [optional] 
**mask_upper** | **int** |  | [optional] 
**seq** | **int** |  | [optional] 

## Example

```python
from graphiant_sdk.models.mana_v2_prefix_set_config_nullable_entry_entry import ManaV2PrefixSetConfigNullableEntryEntry

# TODO update the JSON string below
json = "{}"
# create an instance of ManaV2PrefixSetConfigNullableEntryEntry from a JSON string
mana_v2_prefix_set_config_nullable_entry_entry_instance = ManaV2PrefixSetConfigNullableEntryEntry.from_json(json)
# print the JSON string representation of the object
print(ManaV2PrefixSetConfigNullableEntryEntry.to_json())

# convert the object into a dict
mana_v2_prefix_set_config_nullable_entry_entry_dict = mana_v2_prefix_set_config_nullable_entry_entry_instance.to_dict()
# create an instance of ManaV2PrefixSetConfigNullableEntryEntry from a dict
mana_v2_prefix_set_config_nullable_entry_entry_from_dict = ManaV2PrefixSetConfigNullableEntryEntry.from_dict(mana_v2_prefix_set_config_nullable_entry_entry_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


