# V1ExtranetsB2bCustomerInfoIdGetResponse


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**id** | **int** |  | [optional] 
**provider_enterprise_id** | **int** |  | [optional] 
**service_name** | **str** |  | [optional] 
**status** | **str** |  | [optional] 

## Example

```python
from graphiant_sdk.models.v1_extranets_b2b_customer_info_id_get_response import V1ExtranetsB2bCustomerInfoIdGetResponse

# TODO update the JSON string below
json = "{}"
# create an instance of V1ExtranetsB2bCustomerInfoIdGetResponse from a JSON string
v1_extranets_b2b_customer_info_id_get_response_instance = V1ExtranetsB2bCustomerInfoIdGetResponse.from_json(json)
# print the JSON string representation of the object
print(V1ExtranetsB2bCustomerInfoIdGetResponse.to_json())

# convert the object into a dict
v1_extranets_b2b_customer_info_id_get_response_dict = v1_extranets_b2b_customer_info_id_get_response_instance.to_dict()
# create an instance of V1ExtranetsB2bCustomerInfoIdGetResponse from a dict
v1_extranets_b2b_customer_info_id_get_response_from_dict = V1ExtranetsB2bCustomerInfoIdGetResponse.from_dict(v1_extranets_b2b_customer_info_id_get_response_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


