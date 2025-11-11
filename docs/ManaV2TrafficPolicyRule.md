# ManaV2TrafficPolicyRule


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**action** | [**ManaV2TrafficPolicyAction**](ManaV2TrafficPolicyAction.md) |  | [optional] 
**match** | [**ManaV2PolicyMatch**](ManaV2PolicyMatch.md) |  | [optional] 
**policy_rule_index** | **int** |  | [optional] 
**seq** | **int** |  | [optional] 

## Example

```python
from graphiant_sdk.models.mana_v2_traffic_policy_rule import ManaV2TrafficPolicyRule

# TODO update the JSON string below
json = "{}"
# create an instance of ManaV2TrafficPolicyRule from a JSON string
mana_v2_traffic_policy_rule_instance = ManaV2TrafficPolicyRule.from_json(json)
# print the JSON string representation of the object
print(ManaV2TrafficPolicyRule.to_json())

# convert the object into a dict
mana_v2_traffic_policy_rule_dict = mana_v2_traffic_policy_rule_instance.to_dict()
# create an instance of ManaV2TrafficPolicyRule from a dict
mana_v2_traffic_policy_rule_from_dict = ManaV2TrafficPolicyRule.from_dict(mana_v2_traffic_policy_rule_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


