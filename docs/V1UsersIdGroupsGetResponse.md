# V1UsersIdGroupsGetResponse


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**groups** | [**List[IamGroup]**](IamGroup.md) |  | [optional] 

## Example

```python
from graphiant_sdk.models.v1_users_id_groups_get_response import V1UsersIdGroupsGetResponse

# TODO update the JSON string below
json = "{}"
# create an instance of V1UsersIdGroupsGetResponse from a JSON string
v1_users_id_groups_get_response_instance = V1UsersIdGroupsGetResponse.from_json(json)
# print the JSON string representation of the object
print(V1UsersIdGroupsGetResponse.to_json())

# convert the object into a dict
v1_users_id_groups_get_response_dict = v1_users_id_groups_get_response_instance.to_dict()
# create an instance of V1UsersIdGroupsGetResponse from a dict
v1_users_id_groups_get_response_from_dict = V1UsersIdGroupsGetResponse.from_dict(v1_users_id_groups_get_response_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


