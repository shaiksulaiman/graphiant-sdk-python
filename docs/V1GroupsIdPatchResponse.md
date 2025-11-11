# V1GroupsIdPatchResponse


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**affected_users** | **List[str]** |  | [optional] 
**enterprise_group** | **bool** |  | [optional] 

## Example

```python
from graphiant_sdk.models.v1_groups_id_patch_response import V1GroupsIdPatchResponse

# TODO update the JSON string below
json = "{}"
# create an instance of V1GroupsIdPatchResponse from a JSON string
v1_groups_id_patch_response_instance = V1GroupsIdPatchResponse.from_json(json)
# print the JSON string representation of the object
print(V1GroupsIdPatchResponse.to_json())

# convert the object into a dict
v1_groups_id_patch_response_dict = v1_groups_id_patch_response_instance.to_dict()
# create an instance of V1GroupsIdPatchResponse from a dict
v1_groups_id_patch_response_from_dict = V1GroupsIdPatchResponse.from_dict(v1_groups_id_patch_response_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


