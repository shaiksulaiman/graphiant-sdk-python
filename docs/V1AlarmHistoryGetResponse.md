# V1AlarmHistoryGetResponse


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**history** | [**List[AlarmsAlarmHistory]**](AlarmsAlarmHistory.md) |  | [optional] 

## Example

```python
from graphiant_sdk.models.v1_alarm_history_get_response import V1AlarmHistoryGetResponse

# TODO update the JSON string below
json = "{}"
# create an instance of V1AlarmHistoryGetResponse from a JSON string
v1_alarm_history_get_response_instance = V1AlarmHistoryGetResponse.from_json(json)
# print the JSON string representation of the object
print(V1AlarmHistoryGetResponse.to_json())

# convert the object into a dict
v1_alarm_history_get_response_dict = v1_alarm_history_get_response_instance.to_dict()
# create an instance of V1AlarmHistoryGetResponse from a dict
v1_alarm_history_get_response_from_dict = V1AlarmHistoryGetResponse.from_dict(v1_alarm_history_get_response_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


