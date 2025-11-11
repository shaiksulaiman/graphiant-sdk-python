# V1DevicesDeviceIdVersionsCompareGetRequest


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**from_version** | **int** | 8 bytes (base32 encoded) version number to compare from. (required) | 
**to_version** | **int** | 8 bytes (base32 encoded) version number to compare to. If not set, compare with the latest version. | [optional] 

## Example

```python
from graphiant_sdk.models.v1_devices_device_id_versions_compare_get_request import V1DevicesDeviceIdVersionsCompareGetRequest

# TODO update the JSON string below
json = "{}"
# create an instance of V1DevicesDeviceIdVersionsCompareGetRequest from a JSON string
v1_devices_device_id_versions_compare_get_request_instance = V1DevicesDeviceIdVersionsCompareGetRequest.from_json(json)
# print the JSON string representation of the object
print(V1DevicesDeviceIdVersionsCompareGetRequest.to_json())

# convert the object into a dict
v1_devices_device_id_versions_compare_get_request_dict = v1_devices_device_id_versions_compare_get_request_instance.to_dict()
# create an instance of V1DevicesDeviceIdVersionsCompareGetRequest from a dict
v1_devices_device_id_versions_compare_get_request_from_dict = V1DevicesDeviceIdVersionsCompareGetRequest.from_dict(v1_devices_device_id_versions_compare_get_request_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


