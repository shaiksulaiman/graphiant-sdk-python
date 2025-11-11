# V1DeviceStatusHistoryPostResponse


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**mappings** | [**List[PokedexDeviceHistoryInfo]**](PokedexDeviceHistoryInfo.md) |  | [optional] 

## Example

```python
from graphiant_sdk.models.v1_device_status_history_post_response import V1DeviceStatusHistoryPostResponse

# TODO update the JSON string below
json = "{}"
# create an instance of V1DeviceStatusHistoryPostResponse from a JSON string
v1_device_status_history_post_response_instance = V1DeviceStatusHistoryPostResponse.from_json(json)
# print the JSON string representation of the object
print(V1DeviceStatusHistoryPostResponse.to_json())

# convert the object into a dict
v1_device_status_history_post_response_dict = v1_device_status_history_post_response_instance.to_dict()
# create an instance of V1DeviceStatusHistoryPostResponse from a dict
v1_device_status_history_post_response_from_dict = V1DeviceStatusHistoryPostResponse.from_dict(v1_device_status_history_post_response_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


