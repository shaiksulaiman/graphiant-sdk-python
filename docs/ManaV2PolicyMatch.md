# ManaV2PolicyMatch


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**destination_port** | **int** |  | [optional] 
**destination_prefix** | **str** |  | [optional] 
**icmp_type** | **int** |  | [optional] 
**protocol** | **int** |  | [optional] 
**source_port** | **int** |  | [optional] 
**source_prefix** | **str** |  | [optional] 

## Example

```python
from graphiant_sdk.models.mana_v2_policy_match import ManaV2PolicyMatch

# TODO update the JSON string below
json = "{}"
# create an instance of ManaV2PolicyMatch from a JSON string
mana_v2_policy_match_instance = ManaV2PolicyMatch.from_json(json)
# print the JSON string representation of the object
print(ManaV2PolicyMatch.to_json())

# convert the object into a dict
mana_v2_policy_match_dict = mana_v2_policy_match_instance.to_dict()
# create an instance of ManaV2PolicyMatch from a dict
mana_v2_policy_match_from_dict = ManaV2PolicyMatch.from_dict(mana_v2_policy_match_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


