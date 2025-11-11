# V2NotificationmutelistCreatePostRequest


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**alert_id** | **str** | Alert id of the alert to create allowlist/mutelist for (required) | 
**note_text** | **str** | Optional note | [optional] 

## Example

```python
from graphiant_sdk.models.v2_notificationmutelist_create_post_request import V2NotificationmutelistCreatePostRequest

# TODO update the JSON string below
json = "{}"
# create an instance of V2NotificationmutelistCreatePostRequest from a JSON string
v2_notificationmutelist_create_post_request_instance = V2NotificationmutelistCreatePostRequest.from_json(json)
# print the JSON string representation of the object
print(V2NotificationmutelistCreatePostRequest.to_json())

# convert the object into a dict
v2_notificationmutelist_create_post_request_dict = v2_notificationmutelist_create_post_request_instance.to_dict()
# create an instance of V2NotificationmutelistCreatePostRequest from a dict
v2_notificationmutelist_create_post_request_from_dict = V2NotificationmutelistCreatePostRequest.from_dict(v2_notificationmutelist_create_post_request_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


