# ManaV2ZoneFirewallIpPolicyConfig


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**block_land_attacks** | **bool** |  | [optional] 
**session_limit** | [**ManaV2NullableSessionLimit**](ManaV2NullableSessionLimit.md) |  | [optional] 
**urpf** | **str** |  | [optional] 

## Example

```python
from graphiant_sdk.models.mana_v2_zone_firewall_ip_policy_config import ManaV2ZoneFirewallIpPolicyConfig

# TODO update the JSON string below
json = "{}"
# create an instance of ManaV2ZoneFirewallIpPolicyConfig from a JSON string
mana_v2_zone_firewall_ip_policy_config_instance = ManaV2ZoneFirewallIpPolicyConfig.from_json(json)
# print the JSON string representation of the object
print(ManaV2ZoneFirewallIpPolicyConfig.to_json())

# convert the object into a dict
mana_v2_zone_firewall_ip_policy_config_dict = mana_v2_zone_firewall_ip_policy_config_instance.to_dict()
# create an instance of ManaV2ZoneFirewallIpPolicyConfig from a dict
mana_v2_zone_firewall_ip_policy_config_from_dict = ManaV2ZoneFirewallIpPolicyConfig.from_dict(mana_v2_zone_firewall_ip_policy_config_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


