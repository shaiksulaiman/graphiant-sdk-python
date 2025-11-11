# V1UsersIdGroupsEnterprisesGetResponse


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**groups** | [**List[IamGroup]**](IamGroup.md) |  | [optional] 

## Example

```python
from graphiant_sdk.models.v1_users_id_groups_enterprises_get_response import V1UsersIdGroupsEnterprisesGetResponse

# TODO update the JSON string below
json = "{}"
# create an instance of V1UsersIdGroupsEnterprisesGetResponse from a JSON string
v1_users_id_groups_enterprises_get_response_instance = V1UsersIdGroupsEnterprisesGetResponse.from_json(json)
# print the JSON string representation of the object
print(V1UsersIdGroupsEnterprisesGetResponse.to_json())

# convert the object into a dict
v1_users_id_groups_enterprises_get_response_dict = v1_users_id_groups_enterprises_get_response_instance.to_dict()
# create an instance of V1UsersIdGroupsEnterprisesGetResponse from a dict
v1_users_id_groups_enterprises_get_response_from_dict = V1UsersIdGroupsEnterprisesGetResponse.from_dict(v1_users_id_groups_enterprises_get_response_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


