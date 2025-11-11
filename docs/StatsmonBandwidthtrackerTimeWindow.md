# StatsmonBandwidthtrackerTimeWindow


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**bucket_size_sec** | **int** |  | [optional] 
**old_ts** | [**GoogleProtobufTimestamp**](GoogleProtobufTimestamp.md) |  | [optional] 
**recent_ts** | [**GoogleProtobufTimestamp**](GoogleProtobufTimestamp.md) |  | [optional] 

## Example

```python
from graphiant_sdk.models.statsmon_bandwidthtracker_time_window import StatsmonBandwidthtrackerTimeWindow

# TODO update the JSON string below
json = "{}"
# create an instance of StatsmonBandwidthtrackerTimeWindow from a JSON string
statsmon_bandwidthtracker_time_window_instance = StatsmonBandwidthtrackerTimeWindow.from_json(json)
# print the JSON string representation of the object
print(StatsmonBandwidthtrackerTimeWindow.to_json())

# convert the object into a dict
statsmon_bandwidthtracker_time_window_dict = statsmon_bandwidthtracker_time_window_instance.to_dict()
# create an instance of StatsmonBandwidthtrackerTimeWindow from a dict
statsmon_bandwidthtracker_time_window_from_dict = StatsmonBandwidthtrackerTimeWindow.from_dict(statsmon_bandwidthtracker_time_window_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


