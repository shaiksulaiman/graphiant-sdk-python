# V1DevicesDeviceIdSlicePeersGetResponse


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**slices** | [**List[ManaV2NetworkSlice]**](ManaV2NetworkSlice.md) |  | [optional] 

## Example

```python
from graphiant_sdk.models.v1_devices_device_id_slice_peers_get_response import V1DevicesDeviceIdSlicePeersGetResponse

# TODO update the JSON string below
json = "{}"
# create an instance of V1DevicesDeviceIdSlicePeersGetResponse from a JSON string
v1_devices_device_id_slice_peers_get_response_instance = V1DevicesDeviceIdSlicePeersGetResponse.from_json(json)
# print the JSON string representation of the object
print(V1DevicesDeviceIdSlicePeersGetResponse.to_json())

# convert the object into a dict
v1_devices_device_id_slice_peers_get_response_dict = v1_devices_device_id_slice_peers_get_response_instance.to_dict()
# create an instance of V1DevicesDeviceIdSlicePeersGetResponse from a dict
v1_devices_device_id_slice_peers_get_response_from_dict = V1DevicesDeviceIdSlicePeersGetResponse.from_dict(v1_devices_device_id_slice_peers_get_response_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


