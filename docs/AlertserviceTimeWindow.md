# AlertserviceTimeWindow


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**bucket_size_sec** | **int** |  | [optional] 
**old_ts** | [**GoogleProtobufTimestamp**](GoogleProtobufTimestamp.md) |  | [optional] 
**recent_ts** | [**GoogleProtobufTimestamp**](GoogleProtobufTimestamp.md) |  | [optional] 

## Example

```python
from graphiant_sdk.models.alertservice_time_window import AlertserviceTimeWindow

# TODO update the JSON string below
json = "{}"
# create an instance of AlertserviceTimeWindow from a JSON string
alertservice_time_window_instance = AlertserviceTimeWindow.from_json(json)
# print the JSON string representation of the object
print(AlertserviceTimeWindow.to_json())

# convert the object into a dict
alertservice_time_window_dict = alertservice_time_window_instance.to_dict()
# create an instance of AlertserviceTimeWindow from a dict
alertservice_time_window_from_dict = AlertserviceTimeWindow.from_dict(alertservice_time_window_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


