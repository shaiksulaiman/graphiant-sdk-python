# V1AuthPutResponse


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**affected_users** | **List[str]** |  | [optional] 
**all_groups** | **bool** |  | [optional] 

## Example

```python
from graphiant_sdk.models.v1_auth_put_response import V1AuthPutResponse

# TODO update the JSON string below
json = "{}"
# create an instance of V1AuthPutResponse from a JSON string
v1_auth_put_response_instance = V1AuthPutResponse.from_json(json)
# print the JSON string representation of the object
print(V1AuthPutResponse.to_json())

# convert the object into a dict
v1_auth_put_response_dict = v1_auth_put_response_instance.to_dict()
# create an instance of V1AuthPutResponse from a dict
v1_auth_put_response_from_dict = V1AuthPutResponse.from_dict(v1_auth_put_response_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


