# ManaV2TrafficPolicyRulesetRuleAction


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**backup_circuit** | **str** |  | [optional] 
**backup_circuit_label** | **str** |  | [optional] 
**egress** | **str** |  | [optional] 
**logging** | **bool** |  | [optional] 
**primary_circuit** | **str** |  | [optional] 
**primary_circuit_label** | **str** |  | [optional] 
**remark** | [**ManaV2Dscp**](ManaV2Dscp.md) |  | [optional] 
**sla_class** | **str** |  | [optional] 

## Example

```python
from graphiant_sdk.models.mana_v2_traffic_policy_ruleset_rule_action import ManaV2TrafficPolicyRulesetRuleAction

# TODO update the JSON string below
json = "{}"
# create an instance of ManaV2TrafficPolicyRulesetRuleAction from a JSON string
mana_v2_traffic_policy_ruleset_rule_action_instance = ManaV2TrafficPolicyRulesetRuleAction.from_json(json)
# print the JSON string representation of the object
print(ManaV2TrafficPolicyRulesetRuleAction.to_json())

# convert the object into a dict
mana_v2_traffic_policy_ruleset_rule_action_dict = mana_v2_traffic_policy_ruleset_rule_action_instance.to_dict()
# create an instance of ManaV2TrafficPolicyRulesetRuleAction from a dict
mana_v2_traffic_policy_ruleset_rule_action_from_dict = ManaV2TrafficPolicyRulesetRuleAction.from_dict(mana_v2_traffic_policy_ruleset_rule_action_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


