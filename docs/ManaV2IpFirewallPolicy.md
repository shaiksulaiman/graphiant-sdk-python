# ManaV2IpFirewallPolicy


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**block_land_attacks** | **bool** |  | [optional] 
**session_limit** | **int** |  | [optional] 
**urpf** | **str** |  | [optional] 

## Example

```python
from graphiant_sdk.models.mana_v2_ip_firewall_policy import ManaV2IpFirewallPolicy

# TODO update the JSON string below
json = "{}"
# create an instance of ManaV2IpFirewallPolicy from a JSON string
mana_v2_ip_firewall_policy_instance = ManaV2IpFirewallPolicy.from_json(json)
# print the JSON string representation of the object
print(ManaV2IpFirewallPolicy.to_json())

# convert the object into a dict
mana_v2_ip_firewall_policy_dict = mana_v2_ip_firewall_policy_instance.to_dict()
# create an instance of ManaV2IpFirewallPolicy from a dict
mana_v2_ip_firewall_policy_from_dict = ManaV2IpFirewallPolicy.from_dict(mana_v2_ip_firewall_policy_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


