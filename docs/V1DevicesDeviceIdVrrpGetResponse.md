# V1DevicesDeviceIdVrrpGetResponse


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**vrrp_entry** | [**List[RoutingVrrpEntry]**](RoutingVrrpEntry.md) |  | [optional] 

## Example

```python
from graphiant_sdk.models.v1_devices_device_id_vrrp_get_response import V1DevicesDeviceIdVrrpGetResponse

# TODO update the JSON string below
json = "{}"
# create an instance of V1DevicesDeviceIdVrrpGetResponse from a JSON string
v1_devices_device_id_vrrp_get_response_instance = V1DevicesDeviceIdVrrpGetResponse.from_json(json)
# print the JSON string representation of the object
print(V1DevicesDeviceIdVrrpGetResponse.to_json())

# convert the object into a dict
v1_devices_device_id_vrrp_get_response_dict = v1_devices_device_id_vrrp_get_response_instance.to_dict()
# create an instance of V1DevicesDeviceIdVrrpGetResponse from a dict
v1_devices_device_id_vrrp_get_response_from_dict = V1DevicesDeviceIdVrrpGetResponse.from_dict(v1_devices_device_id_vrrp_get_response_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


