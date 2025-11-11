# ManaV2TrafficPolicyRuleRow


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**device** | [**ManaV2SiteDeviceStub**](ManaV2SiteDeviceStub.md) |  | [optional] 
**traffic_policy_rule** | [**ManaV2TrafficPolicyRule**](ManaV2TrafficPolicyRule.md) |  | [optional] 
**vrf_name** | **str** |  | [optional] 

## Example

```python
from graphiant_sdk.models.mana_v2_traffic_policy_rule_row import ManaV2TrafficPolicyRuleRow

# TODO update the JSON string below
json = "{}"
# create an instance of ManaV2TrafficPolicyRuleRow from a JSON string
mana_v2_traffic_policy_rule_row_instance = ManaV2TrafficPolicyRuleRow.from_json(json)
# print the JSON string representation of the object
print(ManaV2TrafficPolicyRuleRow.to_json())

# convert the object into a dict
mana_v2_traffic_policy_rule_row_dict = mana_v2_traffic_policy_rule_row_instance.to_dict()
# create an instance of ManaV2TrafficPolicyRuleRow from a dict
mana_v2_traffic_policy_rule_row_from_dict = ManaV2TrafficPolicyRuleRow.from_dict(mana_v2_traffic_policy_rule_row_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


