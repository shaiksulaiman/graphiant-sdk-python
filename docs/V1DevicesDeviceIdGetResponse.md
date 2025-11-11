# V1DevicesDeviceIdGetResponse


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**device** | [**ManaV2Device**](ManaV2Device.md) |  | [optional] 

## Example

```python
from graphiant_sdk.models.v1_devices_device_id_get_response import V1DevicesDeviceIdGetResponse

# TODO update the JSON string below
json = "{}"
# create an instance of V1DevicesDeviceIdGetResponse from a JSON string
v1_devices_device_id_get_response_instance = V1DevicesDeviceIdGetResponse.from_json(json)
# print the JSON string representation of the object
print(V1DevicesDeviceIdGetResponse.to_json())

# convert the object into a dict
v1_devices_device_id_get_response_dict = v1_devices_device_id_get_response_instance.to_dict()
# create an instance of V1DevicesDeviceIdGetResponse from a dict
v1_devices_device_id_get_response_from_dict = V1DevicesDeviceIdGetResponse.from_dict(v1_devices_device_id_get_response_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


