# V1AuthGetResponse


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**cert** | **str** |  | [optional] 
**entry_point** | **str** |  | [optional] 
**iam_type** | **str** |  | [optional] 
**issuer** | **str** |  | [optional] 

## Example

```python
from graphiant_sdk.models.v1_auth_get_response import V1AuthGetResponse

# TODO update the JSON string below
json = "{}"
# create an instance of V1AuthGetResponse from a JSON string
v1_auth_get_response_instance = V1AuthGetResponse.from_json(json)
# print the JSON string representation of the object
print(V1AuthGetResponse.to_json())

# convert the object into a dict
v1_auth_get_response_dict = v1_auth_get_response_instance.to_dict()
# create an instance of V1AuthGetResponse from a dict
v1_auth_get_response_from_dict = V1AuthGetResponse.from_dict(v1_auth_get_response_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


