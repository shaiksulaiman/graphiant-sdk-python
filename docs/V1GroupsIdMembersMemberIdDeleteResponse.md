# V1GroupsIdMembersMemberIdDeleteResponse


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**affected_users** | **List[str]** |  | [optional] 
**enterprise_group** | **bool** |  | [optional] 

## Example

```python
from graphiant_sdk.models.v1_groups_id_members_member_id_delete_response import V1GroupsIdMembersMemberIdDeleteResponse

# TODO update the JSON string below
json = "{}"
# create an instance of V1GroupsIdMembersMemberIdDeleteResponse from a JSON string
v1_groups_id_members_member_id_delete_response_instance = V1GroupsIdMembersMemberIdDeleteResponse.from_json(json)
# print the JSON string representation of the object
print(V1GroupsIdMembersMemberIdDeleteResponse.to_json())

# convert the object into a dict
v1_groups_id_members_member_id_delete_response_dict = v1_groups_id_members_member_id_delete_response_instance.to_dict()
# create an instance of V1GroupsIdMembersMemberIdDeleteResponse from a dict
v1_groups_id_members_member_id_delete_response_from_dict = V1GroupsIdMembersMemberIdDeleteResponse.from_dict(v1_groups_id_members_member_id_delete_response_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


