# V1DeviceSnapshotDeviceIdGetResponse


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**snapshots** | [**List[ManaV2DeviceSnapshot]**](ManaV2DeviceSnapshot.md) |  | [optional] 

## Example

```python
from graphiant_sdk.models.v1_device_snapshot_device_id_get_response import V1DeviceSnapshotDeviceIdGetResponse

# TODO update the JSON string below
json = "{}"
# create an instance of V1DeviceSnapshotDeviceIdGetResponse from a JSON string
v1_device_snapshot_device_id_get_response_instance = V1DeviceSnapshotDeviceIdGetResponse.from_json(json)
# print the JSON string representation of the object
print(V1DeviceSnapshotDeviceIdGetResponse.to_json())

# convert the object into a dict
v1_device_snapshot_device_id_get_response_dict = v1_device_snapshot_device_id_get_response_instance.to_dict()
# create an instance of V1DeviceSnapshotDeviceIdGetResponse from a dict
v1_device_snapshot_device_id_get_response_from_dict = V1DeviceSnapshotDeviceIdGetResponse.from_dict(v1_device_snapshot_device_id_get_response_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


