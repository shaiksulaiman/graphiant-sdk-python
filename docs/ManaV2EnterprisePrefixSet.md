# ManaV2EnterprisePrefixSet


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**description** | **str** |  | [optional] 
**entries** | [**List[ManaV2EnterprisePrefixSetEntry]**](ManaV2EnterprisePrefixSetEntry.md) |  | [optional] 
**id** | **int** |  | [optional] 
**mode** | **str** |  | [optional] 
**name** | **str** |  | [optional] 

## Example

```python
from graphiant_sdk.models.mana_v2_enterprise_prefix_set import ManaV2EnterprisePrefixSet

# TODO update the JSON string below
json = "{}"
# create an instance of ManaV2EnterprisePrefixSet from a JSON string
mana_v2_enterprise_prefix_set_instance = ManaV2EnterprisePrefixSet.from_json(json)
# print the JSON string representation of the object
print(ManaV2EnterprisePrefixSet.to_json())

# convert the object into a dict
mana_v2_enterprise_prefix_set_dict = mana_v2_enterprise_prefix_set_instance.to_dict()
# create an instance of ManaV2EnterprisePrefixSet from a dict
mana_v2_enterprise_prefix_set_from_dict = ManaV2EnterprisePrefixSet.from_dict(mana_v2_enterprise_prefix_set_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


