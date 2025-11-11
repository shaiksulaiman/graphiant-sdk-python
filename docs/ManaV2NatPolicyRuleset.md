# ManaV2NatPolicyRuleset


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**description** | **str** |  | [optional] 
**id** | **int** |  | [optional] 
**name** | **str** |  | [optional] 
**rules** | [**List[ManaV2NATPolicyRulesetRule]**](ManaV2NATPolicyRulesetRule.md) |  | [optional] 

## Example

```python
from graphiant_sdk.models.mana_v2_nat_policy_ruleset import ManaV2NatPolicyRuleset

# TODO update the JSON string below
json = "{}"
# create an instance of ManaV2NatPolicyRuleset from a JSON string
mana_v2_nat_policy_ruleset_instance = ManaV2NatPolicyRuleset.from_json(json)
# print the JSON string representation of the object
print(ManaV2NatPolicyRuleset.to_json())

# convert the object into a dict
mana_v2_nat_policy_ruleset_dict = mana_v2_nat_policy_ruleset_instance.to_dict()
# create an instance of ManaV2NatPolicyRuleset from a dict
mana_v2_nat_policy_ruleset_from_dict = ManaV2NatPolicyRuleset.from_dict(mana_v2_nat_policy_ruleset_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


