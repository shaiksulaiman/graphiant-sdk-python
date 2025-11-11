# V1GroupsRootGetResponse


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**groups** | [**List[IamGroup]**](IamGroup.md) |  | [optional] 

## Example

```python
from graphiant_sdk.models.v1_groups_root_get_response import V1GroupsRootGetResponse

# TODO update the JSON string below
json = "{}"
# create an instance of V1GroupsRootGetResponse from a JSON string
v1_groups_root_get_response_instance = V1GroupsRootGetResponse.from_json(json)
# print the JSON string representation of the object
print(V1GroupsRootGetResponse.to_json())

# convert the object into a dict
v1_groups_root_get_response_dict = v1_groups_root_get_response_instance.to_dict()
# create an instance of V1GroupsRootGetResponse from a dict
v1_groups_root_get_response_from_dict = V1GroupsRootGetResponse.from_dict(v1_groups_root_get_response_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


