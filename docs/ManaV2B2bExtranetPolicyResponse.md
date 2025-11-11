# ManaV2B2bExtranetPolicyResponse


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**dns_name** | **str** |  | [optional] 
**inbound_security_rules** | [**List[ManaV2SecurityPolicyRule]**](ManaV2SecurityPolicyRule.md) |  | [optional] 
**policy** | [**ManaV2B2bExtranetProducerPolicy**](ManaV2B2bExtranetProducerPolicy.md) |  | [optional] 
**service_name** | **str** |  | [optional] 
**traffic_rules** | [**List[ManaV2TrafficPolicyRule]**](ManaV2TrafficPolicyRule.md) |  | [optional] 

## Example

```python
from graphiant_sdk.models.mana_v2_b2b_extranet_policy_response import ManaV2B2bExtranetPolicyResponse

# TODO update the JSON string below
json = "{}"
# create an instance of ManaV2B2bExtranetPolicyResponse from a JSON string
mana_v2_b2b_extranet_policy_response_instance = ManaV2B2bExtranetPolicyResponse.from_json(json)
# print the JSON string representation of the object
print(ManaV2B2bExtranetPolicyResponse.to_json())

# convert the object into a dict
mana_v2_b2b_extranet_policy_response_dict = mana_v2_b2b_extranet_policy_response_instance.to_dict()
# create an instance of ManaV2B2bExtranetPolicyResponse from a dict
mana_v2_b2b_extranet_policy_response_from_dict = ManaV2B2bExtranetPolicyResponse.from_dict(mana_v2_b2b_extranet_policy_response_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


