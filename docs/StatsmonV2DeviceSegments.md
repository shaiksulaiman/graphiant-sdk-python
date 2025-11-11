# StatsmonV2DeviceSegments


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**device_id** | **int** |  | [optional] 
**vrf_routes** | [**List[StatsmonV2VrfRoutes]**](StatsmonV2VrfRoutes.md) |  | [optional] 

## Example

```python
from graphiant_sdk.models.statsmon_v2_device_segments import StatsmonV2DeviceSegments

# TODO update the JSON string below
json = "{}"
# create an instance of StatsmonV2DeviceSegments from a JSON string
statsmon_v2_device_segments_instance = StatsmonV2DeviceSegments.from_json(json)
# print the JSON string representation of the object
print(StatsmonV2DeviceSegments.to_json())

# convert the object into a dict
statsmon_v2_device_segments_dict = statsmon_v2_device_segments_instance.to_dict()
# create an instance of StatsmonV2DeviceSegments from a dict
statsmon_v2_device_segments_from_dict = StatsmonV2DeviceSegments.from_dict(statsmon_v2_device_segments_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


