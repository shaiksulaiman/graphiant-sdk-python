# ManaV2SecurityPolicyRulesetRule


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**action** | **str** |  | [optional] 
**description** | **str** |  | [optional] 
**downlink_burst_rate** | **int** |  | [optional] 
**downlink_policer_rate** | **int** |  | [optional] 
**id** | **int** |  | [optional] 
**index** | **int** |  | [optional] 
**logging** | **bool** |  | [optional] 
**match** | [**ManaV2ForwardingPolicyMatch**](ManaV2ForwardingPolicyMatch.md) |  | [optional] 
**name** | **str** |  | [optional] 
**seq** | **int** |  | [optional] 
**uplink_burst_rate** | **int** |  | [optional] 
**uplink_policer_rate** | **int** |  | [optional] 

## Example

```python
from graphiant_sdk.models.mana_v2_security_policy_ruleset_rule import ManaV2SecurityPolicyRulesetRule

# TODO update the JSON string below
json = "{}"
# create an instance of ManaV2SecurityPolicyRulesetRule from a JSON string
mana_v2_security_policy_ruleset_rule_instance = ManaV2SecurityPolicyRulesetRule.from_json(json)
# print the JSON string representation of the object
print(ManaV2SecurityPolicyRulesetRule.to_json())

# convert the object into a dict
mana_v2_security_policy_ruleset_rule_dict = mana_v2_security_policy_ruleset_rule_instance.to_dict()
# create an instance of ManaV2SecurityPolicyRulesetRule from a dict
mana_v2_security_policy_ruleset_rule_from_dict = ManaV2SecurityPolicyRulesetRule.from_dict(mana_v2_security_policy_ruleset_rule_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


