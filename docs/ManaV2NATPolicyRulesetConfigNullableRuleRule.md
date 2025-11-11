# ManaV2NATPolicyRulesetConfigNullableRuleRule


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**advertise_pre_nat_prefixes** | **bool** |  | [optional] 
**description** | **str** |  | [optional] 
**name** | **str** |  | [optional] 
**original_dst_ip_prefix** | **str** |  | [optional] 
**original_src_ip_prefix** | **str** |  | [optional] 
**seq** | **int** |  | [optional] 
**translated_dst_ip_prefix** | **str** |  | [optional] 
**translated_src_ip_prefix** | **str** |  | [optional] 
**type** | **str** |  | [optional] 

## Example

```python
from graphiant_sdk.models.mana_v2_nat_policy_ruleset_config_nullable_rule_rule import ManaV2NATPolicyRulesetConfigNullableRuleRule

# TODO update the JSON string below
json = "{}"
# create an instance of ManaV2NATPolicyRulesetConfigNullableRuleRule from a JSON string
mana_v2_nat_policy_ruleset_config_nullable_rule_rule_instance = ManaV2NATPolicyRulesetConfigNullableRuleRule.from_json(json)
# print the JSON string representation of the object
print(ManaV2NATPolicyRulesetConfigNullableRuleRule.to_json())

# convert the object into a dict
mana_v2_nat_policy_ruleset_config_nullable_rule_rule_dict = mana_v2_nat_policy_ruleset_config_nullable_rule_rule_instance.to_dict()
# create an instance of ManaV2NATPolicyRulesetConfigNullableRuleRule from a dict
mana_v2_nat_policy_ruleset_config_nullable_rule_rule_from_dict = ManaV2NATPolicyRulesetConfigNullableRuleRule.from_dict(mana_v2_nat_policy_ruleset_config_nullable_rule_rule_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


