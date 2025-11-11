# V1DevicesDeviceIdConfigPutResponse


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**job_id** | **int** |  | [optional] 
**workflow_id** | **str** |  | [optional] 

## Example

```python
from graphiant_sdk.models.v1_devices_device_id_config_put_response import V1DevicesDeviceIdConfigPutResponse

# TODO update the JSON string below
json = "{}"
# create an instance of V1DevicesDeviceIdConfigPutResponse from a JSON string
v1_devices_device_id_config_put_response_instance = V1DevicesDeviceIdConfigPutResponse.from_json(json)
# print the JSON string representation of the object
print(V1DevicesDeviceIdConfigPutResponse.to_json())

# convert the object into a dict
v1_devices_device_id_config_put_response_dict = v1_devices_device_id_config_put_response_instance.to_dict()
# create an instance of V1DevicesDeviceIdConfigPutResponse from a dict
v1_devices_device_id_config_put_response_from_dict = V1DevicesDeviceIdConfigPutResponse.from_dict(v1_devices_device_id_config_put_response_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


