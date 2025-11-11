# ManaV2TrafficPolicyRulesetConfigNullableRuleRule


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**action** | [**ManaV2TrafficPolicyRulesetConfigNullableRuleRuleAction**](ManaV2TrafficPolicyRulesetConfigNullableRuleRuleAction.md) |  | [optional] 
**description** | **str** |  | [optional] 
**match** | [**ManaV2ForwardingPolicyMatchConfig**](ManaV2ForwardingPolicyMatchConfig.md) |  | [optional] 
**name** | **str** |  | [optional] 
**seq** | **int** |  | [optional] 

## Example

```python
from graphiant_sdk.models.mana_v2_traffic_policy_ruleset_config_nullable_rule_rule import ManaV2TrafficPolicyRulesetConfigNullableRuleRule

# TODO update the JSON string below
json = "{}"
# create an instance of ManaV2TrafficPolicyRulesetConfigNullableRuleRule from a JSON string
mana_v2_traffic_policy_ruleset_config_nullable_rule_rule_instance = ManaV2TrafficPolicyRulesetConfigNullableRuleRule.from_json(json)
# print the JSON string representation of the object
print(ManaV2TrafficPolicyRulesetConfigNullableRuleRule.to_json())

# convert the object into a dict
mana_v2_traffic_policy_ruleset_config_nullable_rule_rule_dict = mana_v2_traffic_policy_ruleset_config_nullable_rule_rule_instance.to_dict()
# create an instance of ManaV2TrafficPolicyRulesetConfigNullableRuleRule from a dict
mana_v2_traffic_policy_ruleset_config_nullable_rule_rule_from_dict = ManaV2TrafficPolicyRulesetConfigNullableRuleRule.from_dict(mana_v2_traffic_policy_ruleset_config_nullable_rule_rule_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


