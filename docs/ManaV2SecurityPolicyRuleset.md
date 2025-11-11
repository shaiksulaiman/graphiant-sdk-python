# ManaV2SecurityPolicyRuleset


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**description** | **str** |  | [optional] 
**error_message** | **str** |  | [optional] 
**global_id** | **int** |  | [optional] 
**id** | **int** |  | [optional] 
**index** | **int** |  | [optional] 
**name** | **str** |  | [optional] 
**rules** | [**List[ManaV2SecurityPolicyRulesetRule]**](ManaV2SecurityPolicyRulesetRule.md) |  | [optional] 
**status** | **str** |  | [optional] 

## Example

```python
from graphiant_sdk.models.mana_v2_security_policy_ruleset import ManaV2SecurityPolicyRuleset

# TODO update the JSON string below
json = "{}"
# create an instance of ManaV2SecurityPolicyRuleset from a JSON string
mana_v2_security_policy_ruleset_instance = ManaV2SecurityPolicyRuleset.from_json(json)
# print the JSON string representation of the object
print(ManaV2SecurityPolicyRuleset.to_json())

# convert the object into a dict
mana_v2_security_policy_ruleset_dict = mana_v2_security_policy_ruleset_instance.to_dict()
# create an instance of ManaV2SecurityPolicyRuleset from a dict
mana_v2_security_policy_ruleset_from_dict = ManaV2SecurityPolicyRuleset.from_dict(mana_v2_security_policy_ruleset_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


