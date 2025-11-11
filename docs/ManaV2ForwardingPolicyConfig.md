# ManaV2ForwardingPolicyConfig


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**dpi_applications** | [**Dict[str, ManaV2NullableDpiApplicationConfig]**](ManaV2NullableDpiApplicationConfig.md) |  | [optional] 
**network_lists** | [**Dict[str, ManaV2NullableIpNetworkListConfig]**](ManaV2NullableIpNetworkListConfig.md) |  | [optional] 
**port_lists** | [**Dict[str, ManaV2NullableL4PortListConfig]**](ManaV2NullableL4PortListConfig.md) |  | [optional] 
**security_rulesets** | [**Dict[str, ManaV2NullableSecurityPolicyRulesetConfig]**](ManaV2NullableSecurityPolicyRulesetConfig.md) |  | [optional] 
**traffic_rulesets** | [**Dict[str, ManaV2NullableTrafficPolicyRulesetConfig]**](ManaV2NullableTrafficPolicyRulesetConfig.md) |  | [optional] 
**zone_firewalls** | [**Dict[str, ManaV2NullableZoneFirewallConfig]**](ManaV2NullableZoneFirewallConfig.md) |  | [optional] 
**zones** | [**Dict[str, ManaV2NullableSecurityZoneConfig]**](ManaV2NullableSecurityZoneConfig.md) |  | [optional] 

## Example

```python
from graphiant_sdk.models.mana_v2_forwarding_policy_config import ManaV2ForwardingPolicyConfig

# TODO update the JSON string below
json = "{}"
# create an instance of ManaV2ForwardingPolicyConfig from a JSON string
mana_v2_forwarding_policy_config_instance = ManaV2ForwardingPolicyConfig.from_json(json)
# print the JSON string representation of the object
print(ManaV2ForwardingPolicyConfig.to_json())

# convert the object into a dict
mana_v2_forwarding_policy_config_dict = mana_v2_forwarding_policy_config_instance.to_dict()
# create an instance of ManaV2ForwardingPolicyConfig from a dict
mana_v2_forwarding_policy_config_from_dict = ManaV2ForwardingPolicyConfig.from_dict(mana_v2_forwarding_policy_config_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


