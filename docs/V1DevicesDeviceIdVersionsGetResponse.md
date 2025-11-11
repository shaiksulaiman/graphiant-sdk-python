# V1DevicesDeviceIdVersionsGetResponse


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**versions** | [**List[ManaV2VersionMetadata]**](ManaV2VersionMetadata.md) |  | [optional] 

## Example

```python
from graphiant_sdk.models.v1_devices_device_id_versions_get_response import V1DevicesDeviceIdVersionsGetResponse

# TODO update the JSON string below
json = "{}"
# create an instance of V1DevicesDeviceIdVersionsGetResponse from a JSON string
v1_devices_device_id_versions_get_response_instance = V1DevicesDeviceIdVersionsGetResponse.from_json(json)
# print the JSON string representation of the object
print(V1DevicesDeviceIdVersionsGetResponse.to_json())

# convert the object into a dict
v1_devices_device_id_versions_get_response_dict = v1_devices_device_id_versions_get_response_instance.to_dict()
# create an instance of V1DevicesDeviceIdVersionsGetResponse from a dict
v1_devices_device_id_versions_get_response_from_dict = V1DevicesDeviceIdVersionsGetResponse.from_dict(v1_devices_device_id_versions_get_response_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


