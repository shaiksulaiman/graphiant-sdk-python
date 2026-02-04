# V1AuthLoginPostResponse


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**auth** | **bool** |  | [optional] 
**token** | **str** |  | [optional] 
**account_type** | **str** |  | [optional] 
**email** | **str** | User email address (returned for MFA users) | [optional] 
**mfa_type** | **str** | MFA type (returned for MFA users) | [optional] 
**state_token** | **str** | State token for MFA verification (returned for MFA users) | [optional] 
**status** | **str** | Authentication status (returned for MFA users) | [optional] 

## Example

```python
from graphiant_sdk.models.v1_auth_login_post_response import V1AuthLoginPostResponse

# TODO update the JSON string below
json = "{}"
# create an instance of V1AuthLoginPostResponse from a JSON string
v1_auth_login_post_response_instance = V1AuthLoginPostResponse.from_json(json)
# print the JSON string representation of the object
print(V1AuthLoginPostResponse.to_json())

# convert the object into a dict
v1_auth_login_post_response_dict = v1_auth_login_post_response_instance.to_dict()
# create an instance of V1AuthLoginPostResponse from a dict
v1_auth_login_post_response_from_dict = V1AuthLoginPostResponse.from_dict(v1_auth_login_post_response_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


