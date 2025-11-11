# EventEvent


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**actions** | **List[str]** |  | [optional] 
**device_id** | **int** | If set identifies the device ID (required) | [optional] 
**enterprise_id** | **int** | If set identifies the Enterprise ID (required) | [optional] 
**event_data** | **str** | Json encoded event specific data. Should be decoded using event type (required) | [optional] 
**event_id** | **int** | Event Identifier. Not needed while creating. | [optional] 
**event_time** | [**GoogleProtobufTimestamp**](GoogleProtobufTimestamp.md) |  | [optional] 
**hostname** | **str** | hostname of the deviceID | [optional] 
**severity** | **str** | Level of event (required) | [optional] 
**type** | **str** | Identifies the event (required) | [optional] 

## Example

```python
from graphiant_sdk.models.event_event import EventEvent

# TODO update the JSON string below
json = "{}"
# create an instance of EventEvent from a JSON string
event_event_instance = EventEvent.from_json(json)
# print the JSON string representation of the object
print(EventEvent.to_json())

# convert the object into a dict
event_event_dict = event_event_instance.to_dict()
# create an instance of EventEvent from a dict
event_event_from_dict = EventEvent.from_dict(event_event_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


