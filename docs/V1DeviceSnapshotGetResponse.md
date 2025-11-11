# V1DeviceSnapshotGetResponse


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**first_snapshot** | [**ManaV2DeviceSnapshot**](ManaV2DeviceSnapshot.md) |  | [optional] 
**second_snapshot** | [**ManaV2DeviceSnapshot**](ManaV2DeviceSnapshot.md) |  | [optional] 
**third_snapshot** | [**ManaV2DeviceSnapshot**](ManaV2DeviceSnapshot.md) |  | [optional] 

## Example

```python
from graphiant_sdk.models.v1_device_snapshot_get_response import V1DeviceSnapshotGetResponse

# TODO update the JSON string below
json = "{}"
# create an instance of V1DeviceSnapshotGetResponse from a JSON string
v1_device_snapshot_get_response_instance = V1DeviceSnapshotGetResponse.from_json(json)
# print the JSON string representation of the object
print(V1DeviceSnapshotGetResponse.to_json())

# convert the object into a dict
v1_device_snapshot_get_response_dict = v1_device_snapshot_get_response_instance.to_dict()
# create an instance of V1DeviceSnapshotGetResponse from a dict
v1_device_snapshot_get_response_from_dict = V1DeviceSnapshotGetResponse.from_dict(v1_device_snapshot_get_response_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


