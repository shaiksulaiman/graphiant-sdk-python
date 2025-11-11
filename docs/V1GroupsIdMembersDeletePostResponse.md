# V1GroupsIdMembersDeletePostResponse


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**affected_users** | **List[str]** |  | [optional] 
**enterprise_group** | **bool** |  | [optional] 

## Example

```python
from graphiant_sdk.models.v1_groups_id_members_delete_post_response import V1GroupsIdMembersDeletePostResponse

# TODO update the JSON string below
json = "{}"
# create an instance of V1GroupsIdMembersDeletePostResponse from a JSON string
v1_groups_id_members_delete_post_response_instance = V1GroupsIdMembersDeletePostResponse.from_json(json)
# print the JSON string representation of the object
print(V1GroupsIdMembersDeletePostResponse.to_json())

# convert the object into a dict
v1_groups_id_members_delete_post_response_dict = v1_groups_id_members_delete_post_response_instance.to_dict()
# create an instance of V1GroupsIdMembersDeletePostResponse from a dict
v1_groups_id_members_delete_post_response_from_dict = V1GroupsIdMembersDeletePostResponse.from_dict(v1_groups_id_members_delete_post_response_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


