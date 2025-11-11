# ManaV2ForwardingPolicy


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**dpi_applications** | [**List[ManaV2DpiCustomApplication]**](ManaV2DpiCustomApplication.md) |  | [optional] 
**network_lists** | [**List[ManaV2IpNetworkList]**](ManaV2IpNetworkList.md) |  | [optional] 
**port_lists** | [**List[ManaV2L4PortList]**](ManaV2L4PortList.md) |  | [optional] 
**security_rulesets** | [**List[ManaV2SecurityPolicyRuleset]**](ManaV2SecurityPolicyRuleset.md) |  | [optional] 
**traffic_rulesets** | [**List[ManaV2TrafficPolicyRuleset]**](ManaV2TrafficPolicyRuleset.md) |  | [optional] 
**zone_firewalls** | [**List[ManaV2ZoneFirewallPolicy]**](ManaV2ZoneFirewallPolicy.md) |  | [optional] 
**zone_pairs** | [**List[ManaV2SecurityZone]**](ManaV2SecurityZone.md) |  | [optional] 

## Example

```python
from graphiant_sdk.models.mana_v2_forwarding_policy import ManaV2ForwardingPolicy

# TODO update the JSON string below
json = "{}"
# create an instance of ManaV2ForwardingPolicy from a JSON string
mana_v2_forwarding_policy_instance = ManaV2ForwardingPolicy.from_json(json)
# print the JSON string representation of the object
print(ManaV2ForwardingPolicy.to_json())

# convert the object into a dict
mana_v2_forwarding_policy_dict = mana_v2_forwarding_policy_instance.to_dict()
# create an instance of ManaV2ForwardingPolicy from a dict
mana_v2_forwarding_policy_from_dict = ManaV2ForwardingPolicy.from_dict(mana_v2_forwarding_policy_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


