# V1DevicesOauthAuthorizationGetResponse


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**auth_code** | **str** | OAuth authorization code | [optional] 

## Example

```python
from graphiant_sdk.models.v1_devices_oauth_authorization_get_response import V1DevicesOauthAuthorizationGetResponse

# TODO update the JSON string below
json = "{}"
# create an instance of V1DevicesOauthAuthorizationGetResponse from a JSON string
v1_devices_oauth_authorization_get_response_instance = V1DevicesOauthAuthorizationGetResponse.from_json(json)
# print the JSON string representation of the object
print(V1DevicesOauthAuthorizationGetResponse.to_json())

# convert the object into a dict
v1_devices_oauth_authorization_get_response_dict = v1_devices_oauth_authorization_get_response_instance.to_dict()
# create an instance of V1DevicesOauthAuthorizationGetResponse from a dict
v1_devices_oauth_authorization_get_response_from_dict = V1DevicesOauthAuthorizationGetResponse.from_dict(v1_devices_oauth_authorization_get_response_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


