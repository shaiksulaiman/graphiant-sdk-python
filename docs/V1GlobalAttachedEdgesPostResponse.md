# V1GlobalAttachedEdgesPostResponse


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**statuses** | [**List[ManaV2GlobalObjectDeviceStatus]**](ManaV2GlobalObjectDeviceStatus.md) |  | [optional] 

## Example

```python
from graphiant_sdk.models.v1_global_attached_edges_post_response import V1GlobalAttachedEdgesPostResponse

# TODO update the JSON string below
json = "{}"
# create an instance of V1GlobalAttachedEdgesPostResponse from a JSON string
v1_global_attached_edges_post_response_instance = V1GlobalAttachedEdgesPostResponse.from_json(json)
# print the JSON string representation of the object
print(V1GlobalAttachedEdgesPostResponse.to_json())

# convert the object into a dict
v1_global_attached_edges_post_response_dict = v1_global_attached_edges_post_response_instance.to_dict()
# create an instance of V1GlobalAttachedEdgesPostResponse from a dict
v1_global_attached_edges_post_response_from_dict = V1GlobalAttachedEdgesPostResponse.from_dict(v1_global_attached_edges_post_response_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


