# V1AuthMfaTypesGetResponse


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**allowed_mfa_types** | **List[str]** |  | [optional] 

## Example

```python
from graphiant_sdk.models.v1_auth_mfa_types_get_response import V1AuthMfaTypesGetResponse

# TODO update the JSON string below
json = "{}"
# create an instance of V1AuthMfaTypesGetResponse from a JSON string
v1_auth_mfa_types_get_response_instance = V1AuthMfaTypesGetResponse.from_json(json)
# print the JSON string representation of the object
print(V1AuthMfaTypesGetResponse.to_json())

# convert the object into a dict
v1_auth_mfa_types_get_response_dict = v1_auth_mfa_types_get_response_instance.to_dict()
# create an instance of V1AuthMfaTypesGetResponse from a dict
v1_auth_mfa_types_get_response_from_dict = V1AuthMfaTypesGetResponse.from_dict(v1_auth_mfa_types_get_response_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


