# AlarmsAlarmHistory


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**boot_id** | **str** | The boot id for this alarm in the device if alarm is a device alarm. | [optional] 
**description** | **str** | The text representation of this alarm | [optional] 
**is_cleared** | **bool** | This flag shows if the alarm is already cleared. | [optional] 
**perceived_severity** | **str** | Severity of this alarm. | [optional] 
**sequence_number** | **int** | The sequence number for this alarm in the device if alarm is a device alarm. | [optional] 
**time** | [**GoogleProtobufTimestamp**](GoogleProtobufTimestamp.md) |  | [optional] 

## Example

```python
from graphiant_sdk.models.alarms_alarm_history import AlarmsAlarmHistory

# TODO update the JSON string below
json = "{}"
# create an instance of AlarmsAlarmHistory from a JSON string
alarms_alarm_history_instance = AlarmsAlarmHistory.from_json(json)
# print the JSON string representation of the object
print(AlarmsAlarmHistory.to_json())

# convert the object into a dict
alarms_alarm_history_dict = alarms_alarm_history_instance.to_dict()
# create an instance of AlarmsAlarmHistory from a dict
alarms_alarm_history_from_dict = AlarmsAlarmHistory.from_dict(alarms_alarm_history_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


