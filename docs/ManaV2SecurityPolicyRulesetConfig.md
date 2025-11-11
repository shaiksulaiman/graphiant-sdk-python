# ManaV2SecurityPolicyRulesetConfig


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**description** | **str** |  | [optional] 
**global_id** | **int** |  | [optional] 
**is_global_sync** | **bool** |  | [optional] 
**name** | **str** |  | [optional] 
**rules** | [**Dict[str, ManaV2SecurityPolicyRulesetConfigNullableRule]**](ManaV2SecurityPolicyRulesetConfigNullableRule.md) |  | [optional] 

## Example

```python
from graphiant_sdk.models.mana_v2_security_policy_ruleset_config import ManaV2SecurityPolicyRulesetConfig

# TODO update the JSON string below
json = "{}"
# create an instance of ManaV2SecurityPolicyRulesetConfig from a JSON string
mana_v2_security_policy_ruleset_config_instance = ManaV2SecurityPolicyRulesetConfig.from_json(json)
# print the JSON string representation of the object
print(ManaV2SecurityPolicyRulesetConfig.to_json())

# convert the object into a dict
mana_v2_security_policy_ruleset_config_dict = mana_v2_security_policy_ruleset_config_instance.to_dict()
# create an instance of ManaV2SecurityPolicyRulesetConfig from a dict
mana_v2_security_policy_ruleset_config_from_dict = ManaV2SecurityPolicyRulesetConfig.from_dict(mana_v2_security_policy_ruleset_config_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


