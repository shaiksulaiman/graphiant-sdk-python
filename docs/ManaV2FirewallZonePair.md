# ManaV2FirewallZonePair


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**inside** | **str** |  | [optional] 
**outside** | **str** |  | [optional] 
**security_rulesets** | [**List[ManaV2SecurityPolicyRuleset]**](ManaV2SecurityPolicyRuleset.md) |  | [optional] 

## Example

```python
from graphiant_sdk.models.mana_v2_firewall_zone_pair import ManaV2FirewallZonePair

# TODO update the JSON string below
json = "{}"
# create an instance of ManaV2FirewallZonePair from a JSON string
mana_v2_firewall_zone_pair_instance = ManaV2FirewallZonePair.from_json(json)
# print the JSON string representation of the object
print(ManaV2FirewallZonePair.to_json())

# convert the object into a dict
mana_v2_firewall_zone_pair_dict = mana_v2_firewall_zone_pair_instance.to_dict()
# create an instance of ManaV2FirewallZonePair from a dict
mana_v2_firewall_zone_pair_from_dict = ManaV2FirewallZonePair.from_dict(mana_v2_firewall_zone_pair_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


