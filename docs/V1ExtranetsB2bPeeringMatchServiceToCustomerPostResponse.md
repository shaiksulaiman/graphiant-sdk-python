# V1ExtranetsB2bPeeringMatchServiceToCustomerPostResponse


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**match_id** | **int** |  | [optional] 
**service** | [**List[ManaV2B2bExtranetMatchServiceToCustomer]**](ManaV2B2bExtranetMatchServiceToCustomer.md) |  | [optional] 

## Example

```python
from graphiant_sdk.models.v1_extranets_b2b_peering_match_service_to_customer_post_response import V1ExtranetsB2bPeeringMatchServiceToCustomerPostResponse

# TODO update the JSON string below
json = "{}"
# create an instance of V1ExtranetsB2bPeeringMatchServiceToCustomerPostResponse from a JSON string
v1_extranets_b2b_peering_match_service_to_customer_post_response_instance = V1ExtranetsB2bPeeringMatchServiceToCustomerPostResponse.from_json(json)
# print the JSON string representation of the object
print(V1ExtranetsB2bPeeringMatchServiceToCustomerPostResponse.to_json())

# convert the object into a dict
v1_extranets_b2b_peering_match_service_to_customer_post_response_dict = v1_extranets_b2b_peering_match_service_to_customer_post_response_instance.to_dict()
# create an instance of V1ExtranetsB2bPeeringMatchServiceToCustomerPostResponse from a dict
v1_extranets_b2b_peering_match_service_to_customer_post_response_from_dict = V1ExtranetsB2bPeeringMatchServiceToCustomerPostResponse.from_dict(v1_extranets_b2b_peering_match_service_to_customer_post_response_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


