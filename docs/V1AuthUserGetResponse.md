# V1AuthUserGetResponse


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**user_id** | **str** | User identifier | 
**enterprise_id** | **int** | Enterprise identifier | 
**permissions** | [**AuthPermissions**](AuthPermissions.md) |  | 
**time_zone** | **str** | User timezone | 

## Example

```python
from graphiant_sdk.models.v1_auth_user_get_response import V1AuthUserGetResponse

# TODO update the JSON string below
json = "{}"
# create an instance of V1AuthUserGetResponse from a JSON string
v1_auth_user_get_response_instance = V1AuthUserGetResponse.from_json(json)
# print the JSON string representation of the object
print(V1AuthUserGetResponse.to_json())

# convert the object into a dict
v1_auth_user_get_response_dict = v1_auth_user_get_response_instance.to_dict()
# create an instance of V1AuthUserGetResponse from a dict
v1_auth_user_get_response_from_dict = V1AuthUserGetResponse.from_dict(v1_auth_user_get_response_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


