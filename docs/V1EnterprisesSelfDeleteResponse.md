# V1EnterprisesSelfDeleteResponse


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**affected_users** | **List[str]** |  | [optional] 
**all_groups** | **bool** |  | [optional] 

## Example

```python
from graphiant_sdk.models.v1_enterprises_self_delete_response import V1EnterprisesSelfDeleteResponse

# TODO update the JSON string below
json = "{}"
# create an instance of V1EnterprisesSelfDeleteResponse from a JSON string
v1_enterprises_self_delete_response_instance = V1EnterprisesSelfDeleteResponse.from_json(json)
# print the JSON string representation of the object
print(V1EnterprisesSelfDeleteResponse.to_json())

# convert the object into a dict
v1_enterprises_self_delete_response_dict = v1_enterprises_self_delete_response_instance.to_dict()
# create an instance of V1EnterprisesSelfDeleteResponse from a dict
v1_enterprises_self_delete_response_from_dict = V1EnterprisesSelfDeleteResponse.from_dict(v1_enterprises_self_delete_response_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


