# IpfixTimeWindow


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**bucket_size_sec** | **int** |  | [optional] 
**old_ts** | [**GoogleProtobufTimestamp**](GoogleProtobufTimestamp.md) |  | [optional] 
**recent_ts** | [**GoogleProtobufTimestamp**](GoogleProtobufTimestamp.md) |  | [optional] 

## Example

```python
from graphiant_sdk.models.ipfix_time_window import IpfixTimeWindow

# TODO update the JSON string below
json = "{}"
# create an instance of IpfixTimeWindow from a JSON string
ipfix_time_window_instance = IpfixTimeWindow.from_json(json)
# print the JSON string representation of the object
print(IpfixTimeWindow.to_json())

# convert the object into a dict
ipfix_time_window_dict = ipfix_time_window_instance.to_dict()
# create an instance of IpfixTimeWindow from a dict
ipfix_time_window_from_dict = IpfixTimeWindow.from_dict(ipfix_time_window_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


