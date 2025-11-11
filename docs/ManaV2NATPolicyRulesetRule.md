# ManaV2NATPolicyRulesetRule


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**advertise_pre_nat_prefixes** | **bool** |  | [optional] 
**description** | **str** |  | [optional] 
**id** | **int** |  | [optional] 
**index** | **int** |  | [optional] 
**name** | **str** |  | [optional] 
**original_dst_ip_prefix** | **str** |  | [optional] 
**original_src_ip_prefix** | **str** |  | [optional] 
**seq** | **int** |  | [optional] 
**translated_dst_ip_prefix** | **str** |  | [optional] 
**translated_src_ip_prefix** | **str** |  | [optional] 
**type** | **str** |  | [optional] 

## Example

```python
from graphiant_sdk.models.mana_v2_nat_policy_ruleset_rule import ManaV2NATPolicyRulesetRule

# TODO update the JSON string below
json = "{}"
# create an instance of ManaV2NATPolicyRulesetRule from a JSON string
mana_v2_nat_policy_ruleset_rule_instance = ManaV2NATPolicyRulesetRule.from_json(json)
# print the JSON string representation of the object
print(ManaV2NATPolicyRulesetRule.to_json())

# convert the object into a dict
mana_v2_nat_policy_ruleset_rule_dict = mana_v2_nat_policy_ruleset_rule_instance.to_dict()
# create an instance of ManaV2NATPolicyRulesetRule from a dict
mana_v2_nat_policy_ruleset_rule_from_dict = ManaV2NATPolicyRulesetRule.from_dict(mana_v2_nat_policy_ruleset_rule_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


