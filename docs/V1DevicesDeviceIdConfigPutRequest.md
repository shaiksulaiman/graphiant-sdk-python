# V1DevicesDeviceIdConfigPutRequest


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**configuration_metadata** | [**ManaV2ConfigurationMetadata**](ManaV2ConfigurationMetadata.md) |  | [optional] 
**core** | [**ManaV2CoreDeviceConfig**](ManaV2CoreDeviceConfig.md) |  | [optional] 
**description** | **str** |  | [optional] 
**edge** | [**ManaV2EdgeDeviceConfig**](ManaV2EdgeDeviceConfig.md) |  | [optional] 
**local_web_server_password** | **str** |  | [optional] 
**replace** | **bool** |  | [optional] 

## Example

```python
from graphiant_sdk.models.v1_devices_device_id_config_put_request import V1DevicesDeviceIdConfigPutRequest

# TODO update the JSON string below
json = "{}"
# create an instance of V1DevicesDeviceIdConfigPutRequest from a JSON string
v1_devices_device_id_config_put_request_instance = V1DevicesDeviceIdConfigPutRequest.from_json(json)
# print the JSON string representation of the object
print(V1DevicesDeviceIdConfigPutRequest.to_json())

# convert the object into a dict
v1_devices_device_id_config_put_request_dict = v1_devices_device_id_config_put_request_instance.to_dict()
# create an instance of V1DevicesDeviceIdConfigPutRequest from a dict
v1_devices_device_id_config_put_request_from_dict = V1DevicesDeviceIdConfigPutRequest.from_dict(v1_devices_device_id_config_put_request_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


