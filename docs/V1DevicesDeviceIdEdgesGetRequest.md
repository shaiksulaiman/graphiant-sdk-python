# V1DevicesDeviceIdEdgesGetRequest


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**page_request** | [**CommonPageRequest**](CommonPageRequest.md) |  | [optional] 

## Example

```python
from graphiant_sdk.models.v1_devices_device_id_edges_get_request import V1DevicesDeviceIdEdgesGetRequest

# TODO update the JSON string below
json = "{}"
# create an instance of V1DevicesDeviceIdEdgesGetRequest from a JSON string
v1_devices_device_id_edges_get_request_instance = V1DevicesDeviceIdEdgesGetRequest.from_json(json)
# print the JSON string representation of the object
print(V1DevicesDeviceIdEdgesGetRequest.to_json())

# convert the object into a dict
v1_devices_device_id_edges_get_request_dict = v1_devices_device_id_edges_get_request_instance.to_dict()
# create an instance of V1DevicesDeviceIdEdgesGetRequest from a dict
v1_devices_device_id_edges_get_request_from_dict = V1DevicesDeviceIdEdgesGetRequest.from_dict(v1_devices_device_id_edges_get_request_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


