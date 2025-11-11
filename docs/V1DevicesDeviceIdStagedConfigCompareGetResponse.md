# V1DevicesDeviceIdStagedConfigCompareGetResponse


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**diff** | **str** | The diff of latest and staged configurations in JSON patch format. | [optional] 

## Example

```python
from graphiant_sdk.models.v1_devices_device_id_staged_config_compare_get_response import V1DevicesDeviceIdStagedConfigCompareGetResponse

# TODO update the JSON string below
json = "{}"
# create an instance of V1DevicesDeviceIdStagedConfigCompareGetResponse from a JSON string
v1_devices_device_id_staged_config_compare_get_response_instance = V1DevicesDeviceIdStagedConfigCompareGetResponse.from_json(json)
# print the JSON string representation of the object
print(V1DevicesDeviceIdStagedConfigCompareGetResponse.to_json())

# convert the object into a dict
v1_devices_device_id_staged_config_compare_get_response_dict = v1_devices_device_id_staged_config_compare_get_response_instance.to_dict()
# create an instance of V1DevicesDeviceIdStagedConfigCompareGetResponse from a dict
v1_devices_device_id_staged_config_compare_get_response_from_dict = V1DevicesDeviceIdStagedConfigCompareGetResponse.from_dict(v1_devices_device_id_staged_config_compare_get_response_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


