# V1GatewaysReferenceConsumerGetRequest


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**customer_id** | **int** |  | [optional] 
**lan_segment_id** | **int** |  | [optional] 
**region_id** | **int** |  | [optional] 

## Example

```python
from graphiant_sdk.models.v1_gateways_reference_consumer_get_request import V1GatewaysReferenceConsumerGetRequest

# TODO update the JSON string below
json = "{}"
# create an instance of V1GatewaysReferenceConsumerGetRequest from a JSON string
v1_gateways_reference_consumer_get_request_instance = V1GatewaysReferenceConsumerGetRequest.from_json(json)
# print the JSON string representation of the object
print(V1GatewaysReferenceConsumerGetRequest.to_json())

# convert the object into a dict
v1_gateways_reference_consumer_get_request_dict = v1_gateways_reference_consumer_get_request_instance.to_dict()
# create an instance of V1GatewaysReferenceConsumerGetRequest from a dict
v1_gateways_reference_consumer_get_request_from_dict = V1GatewaysReferenceConsumerGetRequest.from_dict(v1_gateways_reference_consumer_get_request_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


