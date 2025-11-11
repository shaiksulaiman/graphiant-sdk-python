# ManaV2ZoneFirewallUdpPolicyConfig


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**unidirectional_flow_limit** | [**ManaV2NullableSessionLimit**](ManaV2NullableSessionLimit.md) |  | [optional] 

## Example

```python
from graphiant_sdk.models.mana_v2_zone_firewall_udp_policy_config import ManaV2ZoneFirewallUdpPolicyConfig

# TODO update the JSON string below
json = "{}"
# create an instance of ManaV2ZoneFirewallUdpPolicyConfig from a JSON string
mana_v2_zone_firewall_udp_policy_config_instance = ManaV2ZoneFirewallUdpPolicyConfig.from_json(json)
# print the JSON string representation of the object
print(ManaV2ZoneFirewallUdpPolicyConfig.to_json())

# convert the object into a dict
mana_v2_zone_firewall_udp_policy_config_dict = mana_v2_zone_firewall_udp_policy_config_instance.to_dict()
# create an instance of ManaV2ZoneFirewallUdpPolicyConfig from a dict
mana_v2_zone_firewall_udp_policy_config_from_dict = ManaV2ZoneFirewallUdpPolicyConfig.from_dict(mana_v2_zone_firewall_udp_policy_config_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


