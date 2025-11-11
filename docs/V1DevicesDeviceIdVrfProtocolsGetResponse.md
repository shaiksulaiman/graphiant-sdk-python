# V1DevicesDeviceIdVrfProtocolsGetResponse


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**bgp** | **bool** |  | [optional] 
**connected** | **bool** |  | [optional] 
**graphiant** | **bool** |  | [optional] 
**ospfv2** | **bool** |  | [optional] 
**ospfv3** | **bool** |  | [optional] 
**static** | **bool** |  | [optional] 

## Example

```python
from graphiant_sdk.models.v1_devices_device_id_vrf_protocols_get_response import V1DevicesDeviceIdVrfProtocolsGetResponse

# TODO update the JSON string below
json = "{}"
# create an instance of V1DevicesDeviceIdVrfProtocolsGetResponse from a JSON string
v1_devices_device_id_vrf_protocols_get_response_instance = V1DevicesDeviceIdVrfProtocolsGetResponse.from_json(json)
# print the JSON string representation of the object
print(V1DevicesDeviceIdVrfProtocolsGetResponse.to_json())

# convert the object into a dict
v1_devices_device_id_vrf_protocols_get_response_dict = v1_devices_device_id_vrf_protocols_get_response_instance.to_dict()
# create an instance of V1DevicesDeviceIdVrfProtocolsGetResponse from a dict
v1_devices_device_id_vrf_protocols_get_response_from_dict = V1DevicesDeviceIdVrfProtocolsGetResponse.from_dict(v1_devices_device_id_vrf_protocols_get_response_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


