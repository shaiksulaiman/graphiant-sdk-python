# V1PortalApikeysGetResponse


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**api_key_info** | [**List[IamApiKeyInfo]**](IamApiKeyInfo.md) |  | [optional] 

## Example

```python
from graphiant_sdk.models.v1_portal_apikeys_get_response import V1PortalApikeysGetResponse

# TODO update the JSON string below
json = "{}"
# create an instance of V1PortalApikeysGetResponse from a JSON string
v1_portal_apikeys_get_response_instance = V1PortalApikeysGetResponse.from_json(json)
# print the JSON string representation of the object
print(V1PortalApikeysGetResponse.to_json())

# convert the object into a dict
v1_portal_apikeys_get_response_dict = v1_portal_apikeys_get_response_instance.to_dict()
# create an instance of V1PortalApikeysGetResponse from a dict
v1_portal_apikeys_get_response_from_dict = V1PortalApikeysGetResponse.from_dict(v1_portal_apikeys_get_response_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


