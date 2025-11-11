# ManaV2ZoneFirewallConfig


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**ip** | [**ManaV2ZoneFirewallIpPolicyConfig**](ManaV2ZoneFirewallIpPolicyConfig.md) |  | [optional] 
**udp** | [**ManaV2ZoneFirewallUdpPolicyConfig**](ManaV2ZoneFirewallUdpPolicyConfig.md) |  | [optional] 

## Example

```python
from graphiant_sdk.models.mana_v2_zone_firewall_config import ManaV2ZoneFirewallConfig

# TODO update the JSON string below
json = "{}"
# create an instance of ManaV2ZoneFirewallConfig from a JSON string
mana_v2_zone_firewall_config_instance = ManaV2ZoneFirewallConfig.from_json(json)
# print the JSON string representation of the object
print(ManaV2ZoneFirewallConfig.to_json())

# convert the object into a dict
mana_v2_zone_firewall_config_dict = mana_v2_zone_firewall_config_instance.to_dict()
# create an instance of ManaV2ZoneFirewallConfig from a dict
mana_v2_zone_firewall_config_from_dict = ManaV2ZoneFirewallConfig.from_dict(mana_v2_zone_firewall_config_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


