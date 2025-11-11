# V1UsersGetResponse


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**users** | [**List[CommonUser]**](CommonUser.md) |  | [optional] 

## Example

```python
from graphiant_sdk.models.v1_users_get_response import V1UsersGetResponse

# TODO update the JSON string below
json = "{}"
# create an instance of V1UsersGetResponse from a JSON string
v1_users_get_response_instance = V1UsersGetResponse.from_json(json)
# print the JSON string representation of the object
print(V1UsersGetResponse.to_json())

# convert the object into a dict
v1_users_get_response_dict = v1_users_get_response_instance.to_dict()
# create an instance of V1UsersGetResponse from a dict
v1_users_get_response_from_dict = V1UsersGetResponse.from_dict(v1_users_get_response_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


