# V2NotificationlistPostResponse


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**notification_list** | [**List[AlertserviceNotificationRecord]**](AlertserviceNotificationRecord.md) |  | [optional] 

## Example

```python
from graphiant_sdk.models.v2_notificationlist_post_response import V2NotificationlistPostResponse

# TODO update the JSON string below
json = "{}"
# create an instance of V2NotificationlistPostResponse from a JSON string
v2_notificationlist_post_response_instance = V2NotificationlistPostResponse.from_json(json)
# print the JSON string representation of the object
print(V2NotificationlistPostResponse.to_json())

# convert the object into a dict
v2_notificationlist_post_response_dict = v2_notificationlist_post_response_instance.to_dict()
# create an instance of V2NotificationlistPostResponse from a dict
v2_notificationlist_post_response_from_dict = V2NotificationlistPostResponse.from_dict(v2_notificationlist_post_response_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


