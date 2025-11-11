# ManaV2PolicyTargetInput


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**excluded_devices** | **List[int]** |  | [optional] 
**prefix_set** | [**ManaV2EnterprisePrefixSetInput**](ManaV2EnterprisePrefixSetInput.md) |  | [optional] 
**sites** | **List[int]** |  | [optional] 

## Example

```python
from graphiant_sdk.models.mana_v2_policy_target_input import ManaV2PolicyTargetInput

# TODO update the JSON string below
json = "{}"
# create an instance of ManaV2PolicyTargetInput from a JSON string
mana_v2_policy_target_input_instance = ManaV2PolicyTargetInput.from_json(json)
# print the JSON string representation of the object
print(ManaV2PolicyTargetInput.to_json())

# convert the object into a dict
mana_v2_policy_target_input_dict = mana_v2_policy_target_input_instance.to_dict()
# create an instance of ManaV2PolicyTargetInput from a dict
mana_v2_policy_target_input_from_dict = ManaV2PolicyTargetInput.from_dict(mana_v2_policy_target_input_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


