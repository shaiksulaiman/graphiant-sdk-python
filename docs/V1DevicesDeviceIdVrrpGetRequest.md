# V1DevicesDeviceIdVrrpGetRequest


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**group_id** | **int** |  | [optional] 
**interface_name** | **str** |  | [optional] 

## Example

```python
from graphiant_sdk.models.v1_devices_device_id_vrrp_get_request import V1DevicesDeviceIdVrrpGetRequest

# TODO update the JSON string below
json = "{}"
# create an instance of V1DevicesDeviceIdVrrpGetRequest from a JSON string
v1_devices_device_id_vrrp_get_request_instance = V1DevicesDeviceIdVrrpGetRequest.from_json(json)
# print the JSON string representation of the object
print(V1DevicesDeviceIdVrrpGetRequest.to_json())

# convert the object into a dict
v1_devices_device_id_vrrp_get_request_dict = v1_devices_device_id_vrrp_get_request_instance.to_dict()
# create an instance of V1DevicesDeviceIdVrrpGetRequest from a dict
v1_devices_device_id_vrrp_get_request_from_dict = V1DevicesDeviceIdVrrpGetRequest.from_dict(v1_devices_device_id_vrrp_get_request_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


