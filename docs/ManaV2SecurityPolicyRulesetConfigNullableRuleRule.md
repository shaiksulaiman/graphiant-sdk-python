# ManaV2SecurityPolicyRulesetConfigNullableRuleRule


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**action** | **str** |  | [optional] 
**description** | **str** |  | [optional] 
**downlink_burst_rate** | [**ManaV2NullableMeterRates**](ManaV2NullableMeterRates.md) |  | [optional] 
**downlink_policer_rate** | [**ManaV2NullableMeterRates**](ManaV2NullableMeterRates.md) |  | [optional] 
**logging** | **bool** |  | [optional] 
**match** | [**ManaV2ForwardingPolicyMatchConfig**](ManaV2ForwardingPolicyMatchConfig.md) |  | [optional] 
**name** | **str** |  | [optional] 
**seq** | **int** |  | [optional] 
**uplink_burst_rate** | [**ManaV2NullableMeterRates**](ManaV2NullableMeterRates.md) |  | [optional] 
**uplink_policer_rate** | [**ManaV2NullableMeterRates**](ManaV2NullableMeterRates.md) |  | [optional] 

## Example

```python
from graphiant_sdk.models.mana_v2_security_policy_ruleset_config_nullable_rule_rule import ManaV2SecurityPolicyRulesetConfigNullableRuleRule

# TODO update the JSON string below
json = "{}"
# create an instance of ManaV2SecurityPolicyRulesetConfigNullableRuleRule from a JSON string
mana_v2_security_policy_ruleset_config_nullable_rule_rule_instance = ManaV2SecurityPolicyRulesetConfigNullableRuleRule.from_json(json)
# print the JSON string representation of the object
print(ManaV2SecurityPolicyRulesetConfigNullableRuleRule.to_json())

# convert the object into a dict
mana_v2_security_policy_ruleset_config_nullable_rule_rule_dict = mana_v2_security_policy_ruleset_config_nullable_rule_rule_instance.to_dict()
# create an instance of ManaV2SecurityPolicyRulesetConfigNullableRuleRule from a dict
mana_v2_security_policy_ruleset_config_nullable_rule_rule_from_dict = ManaV2SecurityPolicyRulesetConfigNullableRuleRule.from_dict(mana_v2_security_policy_ruleset_config_nullable_rule_rule_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


