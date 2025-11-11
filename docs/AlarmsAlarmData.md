# AlarmsAlarmData


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**acknowledged_by** | **str** | The user who acknowledged this alarm. | [optional] 
**alarm_id** | **int** | Unique ID for an alarm. | [optional] 
**alarm_type_id** | **str** | Type ID for an alarm. | [optional] 
**alarm_type_qualifier** | **str** | Unique qualifier for an alarm. It could be null if the alarm id is enough to distinguish the alarms | [optional] 
**alt_component** | **str** | Used if the alarming resource is available over other interfaces. | [optional] 
**boot_id** | **str** | The boot id for this alarm in the device if alarm is a device alarm. | [optional] 
**component** | **str** | The component which raised this alarm. | [optional] 
**created** | [**GoogleProtobufTimestamp**](GoogleProtobufTimestamp.md) |  | [optional] 
**description** | **str** | The text representation of this alarm | [optional] 
**is_cleared** | **bool** | This flag shows if the alarm is already cleared. | [optional] 
**is_resolved** | **bool** | This flag shows if the alarm is already marked as resolved by the customer. | [optional] 
**last_changed** | [**GoogleProtobufTimestamp**](GoogleProtobufTimestamp.md) |  | [optional] 
**last_raised** | [**GoogleProtobufTimestamp**](GoogleProtobufTimestamp.md) |  | [optional] 
**perceived_severity** | **str** | Severity of this alarm. | [optional] 
**resolved_by** | **str** | The user who moved this alert to resolved. | [optional] 
**sequence_number** | **int** | The sequence number for this alarm in the device if alarm is a device alarm. | [optional] 
**where** | **str** | Hostname, site, etc where this alarm is generated for. | [optional] 

## Example

```python
from graphiant_sdk.models.alarms_alarm_data import AlarmsAlarmData

# TODO update the JSON string below
json = "{}"
# create an instance of AlarmsAlarmData from a JSON string
alarms_alarm_data_instance = AlarmsAlarmData.from_json(json)
# print the JSON string representation of the object
print(AlarmsAlarmData.to_json())

# convert the object into a dict
alarms_alarm_data_dict = alarms_alarm_data_instance.to_dict()
# create an instance of AlarmsAlarmData from a dict
alarms_alarm_data_from_dict = AlarmsAlarmData.from_dict(alarms_alarm_data_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


