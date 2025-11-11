# V1DevicesOauthPostResponse


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**access_token** | **str** | OAuth access token | [optional] 
**expires_in** | **int** | Token expiration time in seconds | [optional] 
**token_type** | **str** | Token type | [optional] 

## Example

```python
from graphiant_sdk.models.v1_devices_oauth_post_response import V1DevicesOauthPostResponse

# TODO update the JSON string below
json = "{}"
# create an instance of V1DevicesOauthPostResponse from a JSON string
v1_devices_oauth_post_response_instance = V1DevicesOauthPostResponse.from_json(json)
# print the JSON string representation of the object
print(V1DevicesOauthPostResponse.to_json())

# convert the object into a dict
v1_devices_oauth_post_response_dict = v1_devices_oauth_post_response_instance.to_dict()
# create an instance of V1DevicesOauthPostResponse from a dict
v1_devices_oauth_post_response_from_dict = V1DevicesOauthPostResponse.from_dict(v1_devices_oauth_post_response_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


