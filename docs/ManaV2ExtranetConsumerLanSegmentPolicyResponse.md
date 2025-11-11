# ManaV2ExtranetConsumerLanSegmentPolicyResponse


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**consumer_lan_segment** | **int** |  | [optional] 
**inbound_security_rules** | [**List[ManaV2SecurityPolicyRule]**](ManaV2SecurityPolicyRule.md) |  | [optional] 
**outbound_security_rules** | [**List[ManaV2SecurityPolicyRule]**](ManaV2SecurityPolicyRule.md) |  | [optional] 
**restricted_prefixes** | **List[str]** |  | [optional] 
**rules** | [**List[ManaV2ExtranetConsumerNatRule]**](ManaV2ExtranetConsumerNatRule.md) |  | [optional] 
**traffic_rules** | [**List[ManaV2TrafficPolicyRule]**](ManaV2TrafficPolicyRule.md) |  | [optional] 

## Example

```python
from graphiant_sdk.models.mana_v2_extranet_consumer_lan_segment_policy_response import ManaV2ExtranetConsumerLanSegmentPolicyResponse

# TODO update the JSON string below
json = "{}"
# create an instance of ManaV2ExtranetConsumerLanSegmentPolicyResponse from a JSON string
mana_v2_extranet_consumer_lan_segment_policy_response_instance = ManaV2ExtranetConsumerLanSegmentPolicyResponse.from_json(json)
# print the JSON string representation of the object
print(ManaV2ExtranetConsumerLanSegmentPolicyResponse.to_json())

# convert the object into a dict
mana_v2_extranet_consumer_lan_segment_policy_response_dict = mana_v2_extranet_consumer_lan_segment_policy_response_instance.to_dict()
# create an instance of ManaV2ExtranetConsumerLanSegmentPolicyResponse from a dict
mana_v2_extranet_consumer_lan_segment_policy_response_from_dict = ManaV2ExtranetConsumerLanSegmentPolicyResponse.from_dict(mana_v2_extranet_consumer_lan_segment_policy_response_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


