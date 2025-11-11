# ManaV2B2bExtranetPeeringServicePolicyResponse


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**policy** | [**ManaV2B2bExtranetPeeringServiceProducerPolicy**](ManaV2B2bExtranetPeeringServiceProducerPolicy.md) |  | [optional] 
**service_name** | **str** |  | [optional] 

## Example

```python
from graphiant_sdk.models.mana_v2_b2b_extranet_peering_service_policy_response import ManaV2B2bExtranetPeeringServicePolicyResponse

# TODO update the JSON string below
json = "{}"
# create an instance of ManaV2B2bExtranetPeeringServicePolicyResponse from a JSON string
mana_v2_b2b_extranet_peering_service_policy_response_instance = ManaV2B2bExtranetPeeringServicePolicyResponse.from_json(json)
# print the JSON string representation of the object
print(ManaV2B2bExtranetPeeringServicePolicyResponse.to_json())

# convert the object into a dict
mana_v2_b2b_extranet_peering_service_policy_response_dict = mana_v2_b2b_extranet_peering_service_policy_response_instance.to_dict()
# create an instance of ManaV2B2bExtranetPeeringServicePolicyResponse from a dict
mana_v2_b2b_extranet_peering_service_policy_response_from_dict = ManaV2B2bExtranetPeeringServicePolicyResponse.from_dict(mana_v2_b2b_extranet_peering_service_policy_response_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


