# ManaV2TrafficPolicyRulesetRule


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**action** | [**ManaV2TrafficPolicyRulesetRuleAction**](ManaV2TrafficPolicyRulesetRuleAction.md) |  | [optional] 
**description** | **str** |  | [optional] 
**id** | **int** |  | [optional] 
**index** | **int** |  | [optional] 
**match** | [**ManaV2ForwardingPolicyMatch**](ManaV2ForwardingPolicyMatch.md) |  | [optional] 
**name** | **str** |  | [optional] 
**seq** | **int** |  | [optional] 

## Example

```python
from graphiant_sdk.models.mana_v2_traffic_policy_ruleset_rule import ManaV2TrafficPolicyRulesetRule

# TODO update the JSON string below
json = "{}"
# create an instance of ManaV2TrafficPolicyRulesetRule from a JSON string
mana_v2_traffic_policy_ruleset_rule_instance = ManaV2TrafficPolicyRulesetRule.from_json(json)
# print the JSON string representation of the object
print(ManaV2TrafficPolicyRulesetRule.to_json())

# convert the object into a dict
mana_v2_traffic_policy_ruleset_rule_dict = mana_v2_traffic_policy_ruleset_rule_instance.to_dict()
# create an instance of ManaV2TrafficPolicyRulesetRule from a dict
mana_v2_traffic_policy_ruleset_rule_from_dict = ManaV2TrafficPolicyRulesetRule.from_dict(mana_v2_traffic_policy_ruleset_rule_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


