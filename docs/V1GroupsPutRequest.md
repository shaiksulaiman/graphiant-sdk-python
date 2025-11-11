# V1GroupsPutRequest


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**description** | **str** |  (required) | 
**group_id** | **str** | Only supply if enterprise uses an idp | [optional] 
**group_type** | **str** |  | [optional] 
**manages_enterprises** | **bool** |  | [optional] 
**name** | **str** |  (required) | 
**permissions** | [**CommonPermissions**](CommonPermissions.md) |  | [optional] 
**time_window_end** | **int** |  | [optional] 
**time_window_start** | **int** |  | [optional] 

## Example

```python
from graphiant_sdk.models.v1_groups_put_request import V1GroupsPutRequest

# TODO update the JSON string below
json = "{}"
# create an instance of V1GroupsPutRequest from a JSON string
v1_groups_put_request_instance = V1GroupsPutRequest.from_json(json)
# print the JSON string representation of the object
print(V1GroupsPutRequest.to_json())

# convert the object into a dict
v1_groups_put_request_dict = v1_groups_put_request_instance.to_dict()
# create an instance of V1GroupsPutRequest from a dict
v1_groups_put_request_from_dict = V1GroupsPutRequest.from_dict(v1_groups_put_request_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


