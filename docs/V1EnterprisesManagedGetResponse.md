# V1EnterprisesManagedGetResponse


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**counts** | [**IamCounts**](IamCounts.md) |  | [optional] 
**enterprises** | [**List[IamEnterprise]**](IamEnterprise.md) |  | [optional] 

## Example

```python
from graphiant_sdk.models.v1_enterprises_managed_get_response import V1EnterprisesManagedGetResponse

# TODO update the JSON string below
json = "{}"
# create an instance of V1EnterprisesManagedGetResponse from a JSON string
v1_enterprises_managed_get_response_instance = V1EnterprisesManagedGetResponse.from_json(json)
# print the JSON string representation of the object
print(V1EnterprisesManagedGetResponse.to_json())

# convert the object into a dict
v1_enterprises_managed_get_response_dict = v1_enterprises_managed_get_response_instance.to_dict()
# create an instance of V1EnterprisesManagedGetResponse from a dict
v1_enterprises_managed_get_response_from_dict = V1EnterprisesManagedGetResponse.from_dict(v1_enterprises_managed_get_response_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


