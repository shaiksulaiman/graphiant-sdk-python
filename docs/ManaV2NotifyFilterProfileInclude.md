# ManaV2NotifyFilterProfileInclude


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**id** | **int** |  | [optional] 
**include** | **bool** |  | [optional] 
**subtree** | **str** |  | [optional] 

## Example

```python
from graphiant_sdk.models.mana_v2_notify_filter_profile_include import ManaV2NotifyFilterProfileInclude

# TODO update the JSON string below
json = "{}"
# create an instance of ManaV2NotifyFilterProfileInclude from a JSON string
mana_v2_notify_filter_profile_include_instance = ManaV2NotifyFilterProfileInclude.from_json(json)
# print the JSON string representation of the object
print(ManaV2NotifyFilterProfileInclude.to_json())

# convert the object into a dict
mana_v2_notify_filter_profile_include_dict = mana_v2_notify_filter_profile_include_instance.to_dict()
# create an instance of ManaV2NotifyFilterProfileInclude from a dict
mana_v2_notify_filter_profile_include_from_dict = ManaV2NotifyFilterProfileInclude.from_dict(mana_v2_notify_filter_profile_include_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


