# V1AuthDeleteResponse


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**affected_users** | **List[str]** |  | [optional] 
**all_groups** | **bool** |  | [optional] 

## Example

```python
from graphiant_sdk.models.v1_auth_delete_response import V1AuthDeleteResponse

# TODO update the JSON string below
json = "{}"
# create an instance of V1AuthDeleteResponse from a JSON string
v1_auth_delete_response_instance = V1AuthDeleteResponse.from_json(json)
# print the JSON string representation of the object
print(V1AuthDeleteResponse.to_json())

# convert the object into a dict
v1_auth_delete_response_dict = v1_auth_delete_response_instance.to_dict()
# create an instance of V1AuthDeleteResponse from a dict
v1_auth_delete_response_from_dict = V1AuthDeleteResponse.from_dict(v1_auth_delete_response_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


