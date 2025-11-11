# V1AuthErrorPostResponse


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**auth** | **bool** |  | 
**token** | **str** |  | 
**error** | **str** |  | 

## Example

```python
from graphiant_sdk.models.v1_auth_error_post_response import V1AuthErrorPostResponse

# TODO update the JSON string below
json = "{}"
# create an instance of V1AuthErrorPostResponse from a JSON string
v1_auth_error_post_response_instance = V1AuthErrorPostResponse.from_json(json)
# print the JSON string representation of the object
print(V1AuthErrorPostResponse.to_json())

# convert the object into a dict
v1_auth_error_post_response_dict = v1_auth_error_post_response_instance.to_dict()
# create an instance of V1AuthErrorPostResponse from a dict
v1_auth_error_post_response_from_dict = V1AuthErrorPostResponse.from_dict(v1_auth_error_post_response_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


