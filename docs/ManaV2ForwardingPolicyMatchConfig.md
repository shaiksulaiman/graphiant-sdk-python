# ManaV2ForwardingPolicyMatchConfig


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**application** | [**ManaV2NullableApplicationMatchConfig**](ManaV2NullableApplicationMatchConfig.md) |  | [optional] 
**content_filter** | [**ManaV2NullableContentFilterMatchConfig**](ManaV2NullableContentFilterMatchConfig.md) |  | [optional] 
**destination_network** | [**ManaV2NullableDestinationNetworkMatchConfig**](ManaV2NullableDestinationNetworkMatchConfig.md) |  | [optional] 
**destination_port** | **int** |  | [optional] 
**destination_port_range** | [**ManaV2PortRangeConfig**](ManaV2PortRangeConfig.md) |  | [optional] 
**domain_list** | [**ManaV2NullableDomainListMatchConfig**](ManaV2NullableDomainListMatchConfig.md) |  | [optional] 
**dscp** | [**ManaV2NullableDscpMatchConfig**](ManaV2NullableDscpMatchConfig.md) |  | [optional] 
**icmp_type** | **int** |  | [optional] 
**ip_protocol** | **str** |  | [optional] 
**protocol** | [**ManaV2NullableIpProtocol**](ManaV2NullableIpProtocol.md) |  | [optional] 
**source_network** | [**ManaV2NullableSourceNetworkMatchConfig**](ManaV2NullableSourceNetworkMatchConfig.md) |  | [optional] 
**source_port** | **int** |  | [optional] 
**source_port_range** | [**ManaV2PortRangeConfig**](ManaV2PortRangeConfig.md) |  | [optional] 

## Example

```python
from graphiant_sdk.models.mana_v2_forwarding_policy_match_config import ManaV2ForwardingPolicyMatchConfig

# TODO update the JSON string below
json = "{}"
# create an instance of ManaV2ForwardingPolicyMatchConfig from a JSON string
mana_v2_forwarding_policy_match_config_instance = ManaV2ForwardingPolicyMatchConfig.from_json(json)
# print the JSON string representation of the object
print(ManaV2ForwardingPolicyMatchConfig.to_json())

# convert the object into a dict
mana_v2_forwarding_policy_match_config_dict = mana_v2_forwarding_policy_match_config_instance.to_dict()
# create an instance of ManaV2ForwardingPolicyMatchConfig from a dict
mana_v2_forwarding_policy_match_config_from_dict = ManaV2ForwardingPolicyMatchConfig.from_dict(mana_v2_forwarding_policy_match_config_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


