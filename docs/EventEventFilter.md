# EventEventFilter


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**old_ts** | [**GoogleProtobufTimestamp**](GoogleProtobufTimestamp.md) |  | [optional] 
**recent_ts** | [**GoogleProtobufTimestamp**](GoogleProtobufTimestamp.md) |  | [optional] 
**severity** | **str** |  | [optional] 
**type** | **str** |  | [optional] 

## Example

```python
from graphiant_sdk.models.event_event_filter import EventEventFilter

# TODO update the JSON string below
json = "{}"
# create an instance of EventEventFilter from a JSON string
event_event_filter_instance = EventEventFilter.from_json(json)
# print the JSON string representation of the object
print(EventEventFilter.to_json())

# convert the object into a dict
event_event_filter_dict = event_event_filter_instance.to_dict()
# create an instance of EventEventFilter from a dict
event_event_filter_from_dict = EventEventFilter.from_dict(event_event_filter_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


