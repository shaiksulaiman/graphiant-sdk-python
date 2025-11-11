# V1DevicesDeviceIdConnectivityGetResponse


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**edges** | [**List[ManaV2ConnectivityGraphEdge]**](ManaV2ConnectivityGraphEdge.md) |  | [optional] 
**nodes** | [**List[ManaV2ConnectivityGraphNode]**](ManaV2ConnectivityGraphNode.md) |  | [optional] 

## Example

```python
from graphiant_sdk.models.v1_devices_device_id_connectivity_get_response import V1DevicesDeviceIdConnectivityGetResponse

# TODO update the JSON string below
json = "{}"
# create an instance of V1DevicesDeviceIdConnectivityGetResponse from a JSON string
v1_devices_device_id_connectivity_get_response_instance = V1DevicesDeviceIdConnectivityGetResponse.from_json(json)
# print the JSON string representation of the object
print(V1DevicesDeviceIdConnectivityGetResponse.to_json())

# convert the object into a dict
v1_devices_device_id_connectivity_get_response_dict = v1_devices_device_id_connectivity_get_response_instance.to_dict()
# create an instance of V1DevicesDeviceIdConnectivityGetResponse from a dict
v1_devices_device_id_connectivity_get_response_from_dict = V1DevicesDeviceIdConnectivityGetResponse.from_dict(v1_devices_device_id_connectivity_get_response_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


