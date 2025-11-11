# ManaV2EnterprisePrefixSetDataEntry


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**ip_prefix** | **str** |  | [optional] 
**mask_lower** | **int** |  | [optional] 
**mask_upper** | **int** |  | [optional] 
**seq** | **int** |  | [optional] 

## Example

```python
from graphiant_sdk.models.mana_v2_enterprise_prefix_set_data_entry import ManaV2EnterprisePrefixSetDataEntry

# TODO update the JSON string below
json = "{}"
# create an instance of ManaV2EnterprisePrefixSetDataEntry from a JSON string
mana_v2_enterprise_prefix_set_data_entry_instance = ManaV2EnterprisePrefixSetDataEntry.from_json(json)
# print the JSON string representation of the object
print(ManaV2EnterprisePrefixSetDataEntry.to_json())

# convert the object into a dict
mana_v2_enterprise_prefix_set_data_entry_dict = mana_v2_enterprise_prefix_set_data_entry_instance.to_dict()
# create an instance of ManaV2EnterprisePrefixSetDataEntry from a dict
mana_v2_enterprise_prefix_set_data_entry_from_dict = ManaV2EnterprisePrefixSetDataEntry.from_dict(mana_v2_enterprise_prefix_set_data_entry_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


