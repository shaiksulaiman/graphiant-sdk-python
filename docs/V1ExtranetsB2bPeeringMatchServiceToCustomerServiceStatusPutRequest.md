# V1ExtranetsB2bPeeringMatchServiceToCustomerServiceStatusPutRequest


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**id** | **int** | match ID for the customer&#39;s service subscription (required) | 
**status** | **str** | Customer’s service status: Paused or Active (required) | 

## Example

```python
from graphiant_sdk.models.v1_extranets_b2b_peering_match_service_to_customer_service_status_put_request import V1ExtranetsB2bPeeringMatchServiceToCustomerServiceStatusPutRequest

# TODO update the JSON string below
json = "{}"
# create an instance of V1ExtranetsB2bPeeringMatchServiceToCustomerServiceStatusPutRequest from a JSON string
v1_extranets_b2b_peering_match_service_to_customer_service_status_put_request_instance = V1ExtranetsB2bPeeringMatchServiceToCustomerServiceStatusPutRequest.from_json(json)
# print the JSON string representation of the object
print(V1ExtranetsB2bPeeringMatchServiceToCustomerServiceStatusPutRequest.to_json())

# convert the object into a dict
v1_extranets_b2b_peering_match_service_to_customer_service_status_put_request_dict = v1_extranets_b2b_peering_match_service_to_customer_service_status_put_request_instance.to_dict()
# create an instance of V1ExtranetsB2bPeeringMatchServiceToCustomerServiceStatusPutRequest from a dict
v1_extranets_b2b_peering_match_service_to_customer_service_status_put_request_from_dict = V1ExtranetsB2bPeeringMatchServiceToCustomerServiceStatusPutRequest.from_dict(v1_extranets_b2b_peering_match_service_to_customer_service_status_put_request_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


