# V1GroupsIdMembersGetResponse


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**users** | [**List[CommonUser]**](CommonUser.md) |  | [optional] 

## Example

```python
from graphiant_sdk.models.v1_groups_id_members_get_response import V1GroupsIdMembersGetResponse

# TODO update the JSON string below
json = "{}"
# create an instance of V1GroupsIdMembersGetResponse from a JSON string
v1_groups_id_members_get_response_instance = V1GroupsIdMembersGetResponse.from_json(json)
# print the JSON string representation of the object
print(V1GroupsIdMembersGetResponse.to_json())

# convert the object into a dict
v1_groups_id_members_get_response_dict = v1_groups_id_members_get_response_instance.to_dict()
# create an instance of V1GroupsIdMembersGetResponse from a dict
v1_groups_id_members_get_response_from_dict = V1GroupsIdMembersGetResponse.from_dict(v1_groups_id_members_get_response_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


