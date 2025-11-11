# AssistantTimeWindow


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**bucket_size_sec** | **int** |  | [optional] 
**old_ts** | [**GoogleProtobufTimestamp**](GoogleProtobufTimestamp.md) |  | [optional] 
**recent_ts** | [**GoogleProtobufTimestamp**](GoogleProtobufTimestamp.md) |  | [optional] 

## Example

```python
from graphiant_sdk.models.assistant_time_window import AssistantTimeWindow

# TODO update the JSON string below
json = "{}"
# create an instance of AssistantTimeWindow from a JSON string
assistant_time_window_instance = AssistantTimeWindow.from_json(json)
# print the JSON string representation of the object
print(AssistantTimeWindow.to_json())

# convert the object into a dict
assistant_time_window_dict = assistant_time_window_instance.to_dict()
# create an instance of AssistantTimeWindow from a dict
assistant_time_window_from_dict = AssistantTimeWindow.from_dict(assistant_time_window_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


