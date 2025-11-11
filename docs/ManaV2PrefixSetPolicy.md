# ManaV2PrefixSetPolicy


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**attach_point** | **str** |  | [optional] 
**id** | **int** |  | [optional] 
**name** | **str** |  | [optional] 

## Example

```python
from graphiant_sdk.models.mana_v2_prefix_set_policy import ManaV2PrefixSetPolicy

# TODO update the JSON string below
json = "{}"
# create an instance of ManaV2PrefixSetPolicy from a JSON string
mana_v2_prefix_set_policy_instance = ManaV2PrefixSetPolicy.from_json(json)
# print the JSON string representation of the object
print(ManaV2PrefixSetPolicy.to_json())

# convert the object into a dict
mana_v2_prefix_set_policy_dict = mana_v2_prefix_set_policy_instance.to_dict()
# create an instance of ManaV2PrefixSetPolicy from a dict
mana_v2_prefix_set_policy_from_dict = ManaV2PrefixSetPolicy.from_dict(mana_v2_prefix_set_policy_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


