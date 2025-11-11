# ManaV2NatPolicyRulesetConfig


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**description** | **str** |  | [optional] 
**name** | **str** |  | [optional] 
**rules** | [**Dict[str, ManaV2NATPolicyRulesetConfigNullableRule]**](ManaV2NATPolicyRulesetConfigNullableRule.md) |  | [optional] 

## Example

```python
from graphiant_sdk.models.mana_v2_nat_policy_ruleset_config import ManaV2NatPolicyRulesetConfig

# TODO update the JSON string below
json = "{}"
# create an instance of ManaV2NatPolicyRulesetConfig from a JSON string
mana_v2_nat_policy_ruleset_config_instance = ManaV2NatPolicyRulesetConfig.from_json(json)
# print the JSON string representation of the object
print(ManaV2NatPolicyRulesetConfig.to_json())

# convert the object into a dict
mana_v2_nat_policy_ruleset_config_dict = mana_v2_nat_policy_ruleset_config_instance.to_dict()
# create an instance of ManaV2NatPolicyRulesetConfig from a dict
mana_v2_nat_policy_ruleset_config_from_dict = ManaV2NatPolicyRulesetConfig.from_dict(mana_v2_nat_policy_ruleset_config_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


