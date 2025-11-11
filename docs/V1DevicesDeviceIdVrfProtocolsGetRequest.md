# V1DevicesDeviceIdVrfProtocolsGetRequest


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**vrf_id** | **int** |  | [optional] 
**vrf_name** | **str** |  | [optional] 

## Example

```python
from graphiant_sdk.models.v1_devices_device_id_vrf_protocols_get_request import V1DevicesDeviceIdVrfProtocolsGetRequest

# TODO update the JSON string below
json = "{}"
# create an instance of V1DevicesDeviceIdVrfProtocolsGetRequest from a JSON string
v1_devices_device_id_vrf_protocols_get_request_instance = V1DevicesDeviceIdVrfProtocolsGetRequest.from_json(json)
# print the JSON string representation of the object
print(V1DevicesDeviceIdVrfProtocolsGetRequest.to_json())

# convert the object into a dict
v1_devices_device_id_vrf_protocols_get_request_dict = v1_devices_device_id_vrf_protocols_get_request_instance.to_dict()
# create an instance of V1DevicesDeviceIdVrfProtocolsGetRequest from a dict
v1_devices_device_id_vrf_protocols_get_request_from_dict = V1DevicesDeviceIdVrfProtocolsGetRequest.from_dict(v1_devices_device_id_vrf_protocols_get_request_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


