# V1UsersIdGroupsRootGetResponse


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**groups** | [**List[IamGroup]**](IamGroup.md) |  | [optional] 

## Example

```python
from graphiant_sdk.models.v1_users_id_groups_root_get_response import V1UsersIdGroupsRootGetResponse

# TODO update the JSON string below
json = "{}"
# create an instance of V1UsersIdGroupsRootGetResponse from a JSON string
v1_users_id_groups_root_get_response_instance = V1UsersIdGroupsRootGetResponse.from_json(json)
# print the JSON string representation of the object
print(V1UsersIdGroupsRootGetResponse.to_json())

# convert the object into a dict
v1_users_id_groups_root_get_response_dict = v1_users_id_groups_root_get_response_instance.to_dict()
# create an instance of V1UsersIdGroupsRootGetResponse from a dict
v1_users_id_groups_root_get_response_from_dict = V1UsersIdGroupsRootGetResponse.from_dict(v1_users_id_groups_root_get_response_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


