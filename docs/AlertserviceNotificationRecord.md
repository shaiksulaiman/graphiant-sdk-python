# AlertserviceNotificationRecord


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**alert_type** | **str** | Type of the alert underlying the notification (required) | [optional] 
**mute_count** | **int** | Number of entities notificated muted (required) | [optional] 
**name** | **str** | Name given to the notification record (required) | [optional] 
**notification_body** | [**AlertserviceNotificationBody**](AlertserviceNotificationBody.md) |  | [optional] 
**notification_id** | **str** | Unique id for the notification record (required) | [optional] 
**rule_id** | **str** | The id of the rule on which notification is created (required) | [optional] 
**times_triggered** | **int** | Number of times notification was triggered for the same alert (required) | [optional] 

## Example

```python
from graphiant_sdk.models.alertservice_notification_record import AlertserviceNotificationRecord

# TODO update the JSON string below
json = "{}"
# create an instance of AlertserviceNotificationRecord from a JSON string
alertservice_notification_record_instance = AlertserviceNotificationRecord.from_json(json)
# print the JSON string representation of the object
print(AlertserviceNotificationRecord.to_json())

# convert the object into a dict
alertservice_notification_record_dict = alertservice_notification_record_instance.to_dict()
# create an instance of AlertserviceNotificationRecord from a dict
alertservice_notification_record_from_dict = AlertserviceNotificationRecord.from_dict(alertservice_notification_record_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


