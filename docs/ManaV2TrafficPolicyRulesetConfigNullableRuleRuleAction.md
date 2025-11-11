# ManaV2TrafficPolicyRulesetConfigNullableRuleRuleAction


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**backup_circuit** | [**ManaV2NullableSetCircuitConfig**](ManaV2NullableSetCircuitConfig.md) |  | [optional] 
**backup_circuit_label** | [**ManaV2NullableSetCircuitLabelConfig**](ManaV2NullableSetCircuitLabelConfig.md) |  | [optional] 
**egress** | **str** |  | [optional] 
**logging** | **bool** |  | [optional] 
**primary_circuit** | [**ManaV2NullableSetCircuitConfig**](ManaV2NullableSetCircuitConfig.md) |  | [optional] 
**primary_circuit_label** | [**ManaV2NullableSetCircuitLabelConfig**](ManaV2NullableSetCircuitLabelConfig.md) |  | [optional] 
**remark** | [**ManaV2NullableSetDscpConfig**](ManaV2NullableSetDscpConfig.md) |  | [optional] 
**set_sla_class** | [**ManaV2NullableSetSlaClassConfig**](ManaV2NullableSetSlaClassConfig.md) |  | [optional] 

## Example

```python
from graphiant_sdk.models.mana_v2_traffic_policy_ruleset_config_nullable_rule_rule_action import ManaV2TrafficPolicyRulesetConfigNullableRuleRuleAction

# TODO update the JSON string below
json = "{}"
# create an instance of ManaV2TrafficPolicyRulesetConfigNullableRuleRuleAction from a JSON string
mana_v2_traffic_policy_ruleset_config_nullable_rule_rule_action_instance = ManaV2TrafficPolicyRulesetConfigNullableRuleRuleAction.from_json(json)
# print the JSON string representation of the object
print(ManaV2TrafficPolicyRulesetConfigNullableRuleRuleAction.to_json())

# convert the object into a dict
mana_v2_traffic_policy_ruleset_config_nullable_rule_rule_action_dict = mana_v2_traffic_policy_ruleset_config_nullable_rule_rule_action_instance.to_dict()
# create an instance of ManaV2TrafficPolicyRulesetConfigNullableRuleRuleAction from a dict
mana_v2_traffic_policy_ruleset_config_nullable_rule_rule_action_from_dict = ManaV2TrafficPolicyRulesetConfigNullableRuleRuleAction.from_dict(mana_v2_traffic_policy_ruleset_config_nullable_rule_rule_action_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


