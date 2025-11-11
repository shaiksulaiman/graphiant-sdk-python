# StatsmonV2TimeWindow


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**bucket_size_sec** | **int** |  | [optional] 
**old_ts** | [**GoogleProtobufTimestamp**](GoogleProtobufTimestamp.md) |  | [optional] 
**recent_ts** | [**GoogleProtobufTimestamp**](GoogleProtobufTimestamp.md) |  | [optional] 

## Example

```python
from graphiant_sdk.models.statsmon_v2_time_window import StatsmonV2TimeWindow

# TODO update the JSON string below
json = "{}"
# create an instance of StatsmonV2TimeWindow from a JSON string
statsmon_v2_time_window_instance = StatsmonV2TimeWindow.from_json(json)
# print the JSON string representation of the object
print(StatsmonV2TimeWindow.to_json())

# convert the object into a dict
statsmon_v2_time_window_dict = statsmon_v2_time_window_instance.to_dict()
# create an instance of StatsmonV2TimeWindow from a dict
statsmon_v2_time_window_from_dict = StatsmonV2TimeWindow.from_dict(statsmon_v2_time_window_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


