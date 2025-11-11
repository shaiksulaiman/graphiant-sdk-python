# V1DevicesDeviceIdNdcacheGetResponse


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**nd_entry** | [**List[RoutingNdEntry]**](RoutingNdEntry.md) |  | [optional] 

## Example

```python
from graphiant_sdk.models.v1_devices_device_id_ndcache_get_response import V1DevicesDeviceIdNdcacheGetResponse

# TODO update the JSON string below
json = "{}"
# create an instance of V1DevicesDeviceIdNdcacheGetResponse from a JSON string
v1_devices_device_id_ndcache_get_response_instance = V1DevicesDeviceIdNdcacheGetResponse.from_json(json)
# print the JSON string representation of the object
print(V1DevicesDeviceIdNdcacheGetResponse.to_json())

# convert the object into a dict
v1_devices_device_id_ndcache_get_response_dict = v1_devices_device_id_ndcache_get_response_instance.to_dict()
# create an instance of V1DevicesDeviceIdNdcacheGetResponse from a dict
v1_devices_device_id_ndcache_get_response_from_dict = V1DevicesDeviceIdNdcacheGetResponse.from_dict(v1_devices_device_id_ndcache_get_response_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


