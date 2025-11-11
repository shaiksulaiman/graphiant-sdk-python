# V1EnterprisesGetResponse


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**enterprises** | [**List[IamEnterprise]**](IamEnterprise.md) |  | [optional] 

## Example

```python
from graphiant_sdk.models.v1_enterprises_get_response import V1EnterprisesGetResponse

# TODO update the JSON string below
json = "{}"
# create an instance of V1EnterprisesGetResponse from a JSON string
v1_enterprises_get_response_instance = V1EnterprisesGetResponse.from_json(json)
# print the JSON string representation of the object
print(V1EnterprisesGetResponse.to_json())

# convert the object into a dict
v1_enterprises_get_response_dict = v1_enterprises_get_response_instance.to_dict()
# create an instance of V1EnterprisesGetResponse from a dict
v1_enterprises_get_response_from_dict = V1EnterprisesGetResponse.from_dict(v1_enterprises_get_response_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


