# ManaV2PrefixSetEntry


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**id** | **int** |  | [optional] 
**ip_prefix** | **str** |  | [optional] 
**mask_lower** | **int** |  | [optional] 
**mask_upper** | **int** |  | [optional] 
**seq** | **int** |  | [optional] 

## Example

```python
from graphiant_sdk.models.mana_v2_prefix_set_entry import ManaV2PrefixSetEntry

# TODO update the JSON string below
json = "{}"
# create an instance of ManaV2PrefixSetEntry from a JSON string
mana_v2_prefix_set_entry_instance = ManaV2PrefixSetEntry.from_json(json)
# print the JSON string representation of the object
print(ManaV2PrefixSetEntry.to_json())

# convert the object into a dict
mana_v2_prefix_set_entry_dict = mana_v2_prefix_set_entry_instance.to_dict()
# create an instance of ManaV2PrefixSetEntry from a dict
mana_v2_prefix_set_entry_from_dict = ManaV2PrefixSetEntry.from_dict(mana_v2_prefix_set_entry_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


