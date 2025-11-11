# V1AuthMfaTypesPutRequest


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**allowed_mfa_types** | **List[str]** |  | 

## Example

```python
from graphiant_sdk.models.v1_auth_mfa_types_put_request import V1AuthMfaTypesPutRequest

# TODO update the JSON string below
json = "{}"
# create an instance of V1AuthMfaTypesPutRequest from a JSON string
v1_auth_mfa_types_put_request_instance = V1AuthMfaTypesPutRequest.from_json(json)
# print the JSON string representation of the object
print(V1AuthMfaTypesPutRequest.to_json())

# convert the object into a dict
v1_auth_mfa_types_put_request_dict = v1_auth_mfa_types_put_request_instance.to_dict()
# create an instance of V1AuthMfaTypesPutRequest from a dict
v1_auth_mfa_types_put_request_from_dict = V1AuthMfaTypesPutRequest.from_dict(v1_auth_mfa_types_put_request_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


