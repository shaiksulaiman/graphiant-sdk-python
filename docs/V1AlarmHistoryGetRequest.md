# V1AlarmHistoryGetRequest


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**alarm_id** | **int** | Unique ID for an alarm. | [optional] 

## Example

```python
from graphiant_sdk.models.v1_alarm_history_get_request import V1AlarmHistoryGetRequest

# TODO update the JSON string below
json = "{}"
# create an instance of V1AlarmHistoryGetRequest from a JSON string
v1_alarm_history_get_request_instance = V1AlarmHistoryGetRequest.from_json(json)
# print the JSON string representation of the object
print(V1AlarmHistoryGetRequest.to_json())

# convert the object into a dict
v1_alarm_history_get_request_dict = v1_alarm_history_get_request_instance.to_dict()
# create an instance of V1AlarmHistoryGetRequest from a dict
v1_alarm_history_get_request_from_dict = V1AlarmHistoryGetRequest.from_dict(v1_alarm_history_get_request_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


