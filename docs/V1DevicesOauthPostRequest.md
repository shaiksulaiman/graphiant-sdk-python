# V1DevicesOauthPostRequest


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**grant_type** | **str** | OAuth grant type | 
**scope** | **str** | OAuth scope containing device type, UUID, and hostname | 
**state** | **str** | OAuth state parameter | [optional] 
**code_verify** | **str** | OAuth code verifier | [optional] 
**pt** | **str** | Platform type | [optional] 
**bm** | **str** | Boot mode | [optional] 

## Example

```python
from graphiant_sdk.models.v1_devices_oauth_post_request import V1DevicesOauthPostRequest

# TODO update the JSON string below
json = "{}"
# create an instance of V1DevicesOauthPostRequest from a JSON string
v1_devices_oauth_post_request_instance = V1DevicesOauthPostRequest.from_json(json)
# print the JSON string representation of the object
print(V1DevicesOauthPostRequest.to_json())

# convert the object into a dict
v1_devices_oauth_post_request_dict = v1_devices_oauth_post_request_instance.to_dict()
# create an instance of V1DevicesOauthPostRequest from a dict
v1_devices_oauth_post_request_from_dict = V1DevicesOauthPostRequest.from_dict(v1_devices_oauth_post_request_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


