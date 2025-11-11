# ManaV2PolicyTarget


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**excluded_devices** | [**List[ManaV2Device]**](ManaV2Device.md) |  | [optional] 
**prefix_set** | [**ManaV2EnterprisePrefixSet**](ManaV2EnterprisePrefixSet.md) |  | [optional] 
**sites** | [**List[ManaV2Site]**](ManaV2Site.md) |  | [optional] 

## Example

```python
from graphiant_sdk.models.mana_v2_policy_target import ManaV2PolicyTarget

# TODO update the JSON string below
json = "{}"
# create an instance of ManaV2PolicyTarget from a JSON string
mana_v2_policy_target_instance = ManaV2PolicyTarget.from_json(json)
# print the JSON string representation of the object
print(ManaV2PolicyTarget.to_json())

# convert the object into a dict
mana_v2_policy_target_dict = mana_v2_policy_target_instance.to_dict()
# create an instance of ManaV2PolicyTarget from a dict
mana_v2_policy_target_from_dict = ManaV2PolicyTarget.from_dict(mana_v2_policy_target_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


