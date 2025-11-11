# ManaV2ForwardingPolicyMatch


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**application** | **str** |  | [optional] 
**destination_network** | **str** |  | [optional] 
**destination_port** | **int** |  | [optional] 
**destination_port_range** | [**ManaV2PortRange**](ManaV2PortRange.md) |  | [optional] 
**domain_category_ids** | **List[int]** |  | [optional] 
**domain_wildcards** | **List[str]** |  | [optional] 
**dscp** | [**ManaV2Dscp**](ManaV2Dscp.md) |  | [optional] 
**icmp_type** | **int** |  | [optional] 
**ip_protocol** | **str** |  | [optional] 
**protocol** | **str** |  | [optional] 
**source_network** | **str** |  | [optional] 
**source_port** | **int** |  | [optional] 
**source_port_range** | [**ManaV2PortRange**](ManaV2PortRange.md) |  | [optional] 

## Example

```python
from graphiant_sdk.models.mana_v2_forwarding_policy_match import ManaV2ForwardingPolicyMatch

# TODO update the JSON string below
json = "{}"
# create an instance of ManaV2ForwardingPolicyMatch from a JSON string
mana_v2_forwarding_policy_match_instance = ManaV2ForwardingPolicyMatch.from_json(json)
# print the JSON string representation of the object
print(ManaV2ForwardingPolicyMatch.to_json())

# convert the object into a dict
mana_v2_forwarding_policy_match_dict = mana_v2_forwarding_policy_match_instance.to_dict()
# create an instance of ManaV2ForwardingPolicyMatch from a dict
mana_v2_forwarding_policy_match_from_dict = ManaV2ForwardingPolicyMatch.from_dict(mana_v2_forwarding_policy_match_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


