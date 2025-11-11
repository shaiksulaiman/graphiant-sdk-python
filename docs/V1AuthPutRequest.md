# V1AuthPutRequest


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**cert** | **str** |  (required) | 
**entry_point** | **str** |  (required) | 
**iam_type** | **str** |  (required) | 
**issuer** | **str** |  (required) | 

## Example

```python
from graphiant_sdk.models.v1_auth_put_request import V1AuthPutRequest

# TODO update the JSON string below
json = "{}"
# create an instance of V1AuthPutRequest from a JSON string
v1_auth_put_request_instance = V1AuthPutRequest.from_json(json)
# print the JSON string representation of the object
print(V1AuthPutRequest.to_json())

# convert the object into a dict
v1_auth_put_request_dict = v1_auth_put_request_instance.to_dict()
# create an instance of V1AuthPutRequest from a dict
v1_auth_put_request_from_dict = V1AuthPutRequest.from_dict(v1_auth_put_request_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


