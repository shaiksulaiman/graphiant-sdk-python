# ManaV2SecurityPolicyRuleRow


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**device** | [**ManaV2SiteDeviceStub**](ManaV2SiteDeviceStub.md) |  | [optional] 
**security_policy_rule** | [**ManaV2SecurityPolicyRule**](ManaV2SecurityPolicyRule.md) |  | [optional] 
**vrf_name** | **str** |  | [optional] 

## Example

```python
from graphiant_sdk.models.mana_v2_security_policy_rule_row import ManaV2SecurityPolicyRuleRow

# TODO update the JSON string below
json = "{}"
# create an instance of ManaV2SecurityPolicyRuleRow from a JSON string
mana_v2_security_policy_rule_row_instance = ManaV2SecurityPolicyRuleRow.from_json(json)
# print the JSON string representation of the object
print(ManaV2SecurityPolicyRuleRow.to_json())

# convert the object into a dict
mana_v2_security_policy_rule_row_dict = mana_v2_security_policy_rule_row_instance.to_dict()
# create an instance of ManaV2SecurityPolicyRuleRow from a dict
mana_v2_security_policy_rule_row_from_dict = ManaV2SecurityPolicyRuleRow.from_dict(mana_v2_security_policy_rule_row_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


