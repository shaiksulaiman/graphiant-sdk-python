# V1AuthPatchResponse


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**affected_users** | **List[str]** |  | [optional] 
**all_groups** | **bool** |  | [optional] 

## Example

```python
from graphiant_sdk.models.v1_auth_patch_response import V1AuthPatchResponse

# TODO update the JSON string below
json = "{}"
# create an instance of V1AuthPatchResponse from a JSON string
v1_auth_patch_response_instance = V1AuthPatchResponse.from_json(json)
# print the JSON string representation of the object
print(V1AuthPatchResponse.to_json())

# convert the object into a dict
v1_auth_patch_response_dict = v1_auth_patch_response_instance.to_dict()
# create an instance of V1AuthPatchResponse from a dict
v1_auth_patch_response_from_dict = V1AuthPatchResponse.from_dict(v1_auth_patch_response_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


