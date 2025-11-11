# V1UsersEmailPasswordPatchRequest


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**password** | **str** | New password for the user | 

## Example

```python
from graphiant_sdk.models.v1_users_email_password_patch_request import V1UsersEmailPasswordPatchRequest

# TODO update the JSON string below
json = "{}"
# create an instance of V1UsersEmailPasswordPatchRequest from a JSON string
v1_users_email_password_patch_request_instance = V1UsersEmailPasswordPatchRequest.from_json(json)
# print the JSON string representation of the object
print(V1UsersEmailPasswordPatchRequest.to_json())

# convert the object into a dict
v1_users_email_password_patch_request_dict = v1_users_email_password_patch_request_instance.to_dict()
# create an instance of V1UsersEmailPasswordPatchRequest from a dict
v1_users_email_password_patch_request_from_dict = V1UsersEmailPasswordPatchRequest.from_dict(v1_users_email_password_patch_request_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


