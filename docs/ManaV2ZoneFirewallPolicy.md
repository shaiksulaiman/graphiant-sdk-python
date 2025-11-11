# ManaV2ZoneFirewallPolicy


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**ip** | [**ManaV2IpFirewallPolicy**](ManaV2IpFirewallPolicy.md) |  | [optional] 
**udp** | [**ManaV2UdpFlowTable**](ManaV2UdpFlowTable.md) |  | [optional] 
**zone_name** | **str** |  | [optional] 

## Example

```python
from graphiant_sdk.models.mana_v2_zone_firewall_policy import ManaV2ZoneFirewallPolicy

# TODO update the JSON string below
json = "{}"
# create an instance of ManaV2ZoneFirewallPolicy from a JSON string
mana_v2_zone_firewall_policy_instance = ManaV2ZoneFirewallPolicy.from_json(json)
# print the JSON string representation of the object
print(ManaV2ZoneFirewallPolicy.to_json())

# convert the object into a dict
mana_v2_zone_firewall_policy_dict = mana_v2_zone_firewall_policy_instance.to_dict()
# create an instance of ManaV2ZoneFirewallPolicy from a dict
mana_v2_zone_firewall_policy_from_dict = ManaV2ZoneFirewallPolicy.from_dict(mana_v2_zone_firewall_policy_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


