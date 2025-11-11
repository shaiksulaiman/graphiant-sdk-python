# V1AuthLoginPreGetResponse


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**method** | **str** | Authentication method to use | 
**email** | **str** | User email address | 
**iam** | **str** | Identity provider name (Azure/Okta) | [optional] 
**relay_state** | **str** | State to relay after authentication | [optional] 
**entry_point** | **str** | SSO entry point URL | [optional] 

## Example

```python
from graphiant_sdk.models.v1_auth_login_pre_get_response import V1AuthLoginPreGetResponse

# TODO update the JSON string below
json = "{}"
# create an instance of V1AuthLoginPreGetResponse from a JSON string
v1_auth_login_pre_get_response_instance = V1AuthLoginPreGetResponse.from_json(json)
# print the JSON string representation of the object
print(V1AuthLoginPreGetResponse.to_json())

# convert the object into a dict
v1_auth_login_pre_get_response_dict = v1_auth_login_pre_get_response_instance.to_dict()
# create an instance of V1AuthLoginPreGetResponse from a dict
v1_auth_login_pre_get_response_from_dict = V1AuthLoginPreGetResponse.from_dict(v1_auth_login_pre_get_response_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


