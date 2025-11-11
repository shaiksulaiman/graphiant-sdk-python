# ManaV2NatPolicy


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**nat_policy_rulesets** | [**List[ManaV2NatPolicyRuleset]**](ManaV2NatPolicyRuleset.md) |  | [optional] 

## Example

```python
from graphiant_sdk.models.mana_v2_nat_policy import ManaV2NatPolicy

# TODO update the JSON string below
json = "{}"
# create an instance of ManaV2NatPolicy from a JSON string
mana_v2_nat_policy_instance = ManaV2NatPolicy.from_json(json)
# print the JSON string representation of the object
print(ManaV2NatPolicy.to_json())

# convert the object into a dict
mana_v2_nat_policy_dict = mana_v2_nat_policy_instance.to_dict()
# create an instance of ManaV2NatPolicy from a dict
mana_v2_nat_policy_from_dict = ManaV2NatPolicy.from_dict(mana_v2_nat_policy_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


