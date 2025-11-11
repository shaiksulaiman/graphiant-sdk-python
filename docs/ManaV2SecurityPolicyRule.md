# ManaV2SecurityPolicyRule


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**action** | **str** |  | [optional] 
**implicit** | **bool** |  | [optional] 
**match** | [**ManaV2PolicyMatch**](ManaV2PolicyMatch.md) |  | [optional] 
**policy_rule_index** | **int** |  | [optional] 
**seq** | **int** |  | [optional] 

## Example

```python
from graphiant_sdk.models.mana_v2_security_policy_rule import ManaV2SecurityPolicyRule

# TODO update the JSON string below
json = "{}"
# create an instance of ManaV2SecurityPolicyRule from a JSON string
mana_v2_security_policy_rule_instance = ManaV2SecurityPolicyRule.from_json(json)
# print the JSON string representation of the object
print(ManaV2SecurityPolicyRule.to_json())

# convert the object into a dict
mana_v2_security_policy_rule_dict = mana_v2_security_policy_rule_instance.to_dict()
# create an instance of ManaV2SecurityPolicyRule from a dict
mana_v2_security_policy_rule_from_dict = ManaV2SecurityPolicyRule.from_dict(mana_v2_security_policy_rule_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


