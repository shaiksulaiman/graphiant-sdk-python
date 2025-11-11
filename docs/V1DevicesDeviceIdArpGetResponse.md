# V1DevicesDeviceIdArpGetResponse


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**arp_entry** | [**List[RoutingArpEntry]**](RoutingArpEntry.md) |  | [optional] 

## Example

```python
from graphiant_sdk.models.v1_devices_device_id_arp_get_response import V1DevicesDeviceIdArpGetResponse

# TODO update the JSON string below
json = "{}"
# create an instance of V1DevicesDeviceIdArpGetResponse from a JSON string
v1_devices_device_id_arp_get_response_instance = V1DevicesDeviceIdArpGetResponse.from_json(json)
# print the JSON string representation of the object
print(V1DevicesDeviceIdArpGetResponse.to_json())

# convert the object into a dict
v1_devices_device_id_arp_get_response_dict = v1_devices_device_id_arp_get_response_instance.to_dict()
# create an instance of V1DevicesDeviceIdArpGetResponse from a dict
v1_devices_device_id_arp_get_response_from_dict = V1DevicesDeviceIdArpGetResponse.from_dict(v1_devices_device_id_arp_get_response_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


