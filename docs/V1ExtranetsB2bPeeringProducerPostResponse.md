# V1ExtranetsB2bPeeringProducerPostResponse


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**activity_id** | **str** |  | [optional] 
**id** | **int** |  | [optional] 
**policy** | [**ManaV2B2bExtranetPeeringServicePolicyResponse**](ManaV2B2bExtranetPeeringServicePolicyResponse.md) |  | [optional] 

## Example

```python
from graphiant_sdk.models.v1_extranets_b2b_peering_producer_post_response import V1ExtranetsB2bPeeringProducerPostResponse

# TODO update the JSON string below
json = "{}"
# create an instance of V1ExtranetsB2bPeeringProducerPostResponse from a JSON string
v1_extranets_b2b_peering_producer_post_response_instance = V1ExtranetsB2bPeeringProducerPostResponse.from_json(json)
# print the JSON string representation of the object
print(V1ExtranetsB2bPeeringProducerPostResponse.to_json())

# convert the object into a dict
v1_extranets_b2b_peering_producer_post_response_dict = v1_extranets_b2b_peering_producer_post_response_instance.to_dict()
# create an instance of V1ExtranetsB2bPeeringProducerPostResponse from a dict
v1_extranets_b2b_peering_producer_post_response_from_dict = V1ExtranetsB2bPeeringProducerPostResponse.from_dict(v1_extranets_b2b_peering_producer_post_response_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


