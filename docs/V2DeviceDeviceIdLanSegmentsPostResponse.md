# V2DeviceDeviceIdLanSegmentsPostResponse


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**device_segments** | [**List[StatsmonV2DeviceSegments]**](StatsmonV2DeviceSegments.md) |  | [optional] 

## Example

```python
from graphiant_sdk.models.v2_device_device_id_lan_segments_post_response import V2DeviceDeviceIdLanSegmentsPostResponse

# TODO update the JSON string below
json = "{}"
# create an instance of V2DeviceDeviceIdLanSegmentsPostResponse from a JSON string
v2_device_device_id_lan_segments_post_response_instance = V2DeviceDeviceIdLanSegmentsPostResponse.from_json(json)
# print the JSON string representation of the object
print(V2DeviceDeviceIdLanSegmentsPostResponse.to_json())

# convert the object into a dict
v2_device_device_id_lan_segments_post_response_dict = v2_device_device_id_lan_segments_post_response_instance.to_dict()
# create an instance of V2DeviceDeviceIdLanSegmentsPostResponse from a dict
v2_device_device_id_lan_segments_post_response_from_dict = V2DeviceDeviceIdLanSegmentsPostResponse.from_dict(v2_device_device_id_lan_segments_post_response_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


