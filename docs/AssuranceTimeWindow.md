# AssuranceTimeWindow


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**bucket_size_sec** | **int** |  | [optional] 
**old_ts** | [**GoogleProtobufTimestamp**](GoogleProtobufTimestamp.md) |  | [optional] 
**recent_ts** | [**GoogleProtobufTimestamp**](GoogleProtobufTimestamp.md) |  | [optional] 

## Example

```python
from graphiant_sdk.models.assurance_time_window import AssuranceTimeWindow

# TODO update the JSON string below
json = "{}"
# create an instance of AssuranceTimeWindow from a JSON string
assurance_time_window_instance = AssuranceTimeWindow.from_json(json)
# print the JSON string representation of the object
print(AssuranceTimeWindow.to_json())

# convert the object into a dict
assurance_time_window_dict = assurance_time_window_instance.to_dict()
# create an instance of AssuranceTimeWindow from a dict
assurance_time_window_from_dict = AssuranceTimeWindow.from_dict(assurance_time_window_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


