# ManaV2PrefixSet


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**description** | **str** |  | [optional] 
**entries** | [**List[ManaV2PrefixSetEntry]**](ManaV2PrefixSetEntry.md) |  | [optional] 
**error_message** | **str** |  | [optional] 
**global_id** | **int** |  | [optional] 
**id** | **int** |  | [optional] 
**mode** | **str** |  | [optional] 
**name** | **str** |  | [optional] 
**policies** | [**List[ManaV2PrefixSetPolicy]**](ManaV2PrefixSetPolicy.md) |  | [optional] 
**policy_count** | **int** |  | [optional] 
**status** | **str** |  | [optional] 

## Example

```python
from graphiant_sdk.models.mana_v2_prefix_set import ManaV2PrefixSet

# TODO update the JSON string below
json = "{}"
# create an instance of ManaV2PrefixSet from a JSON string
mana_v2_prefix_set_instance = ManaV2PrefixSet.from_json(json)
# print the JSON string representation of the object
print(ManaV2PrefixSet.to_json())

# convert the object into a dict
mana_v2_prefix_set_dict = mana_v2_prefix_set_instance.to_dict()
# create an instance of ManaV2PrefixSet from a dict
mana_v2_prefix_set_from_dict = ManaV2PrefixSet.from_dict(mana_v2_prefix_set_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


