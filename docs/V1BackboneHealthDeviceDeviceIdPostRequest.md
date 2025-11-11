# V1BackboneHealthDeviceDeviceIdPostRequest


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**time_window** | [**StatsmonTroubleshootingTimeWindow**](StatsmonTroubleshootingTimeWindow.md) |  | [optional] 

## Example

```python
from graphiant_sdk.models.v1_backbone_health_device_device_id_post_request import V1BackboneHealthDeviceDeviceIdPostRequest

# TODO update the JSON string below
json = "{}"
# create an instance of V1BackboneHealthDeviceDeviceIdPostRequest from a JSON string
v1_backbone_health_device_device_id_post_request_instance = V1BackboneHealthDeviceDeviceIdPostRequest.from_json(json)
# print the JSON string representation of the object
print(V1BackboneHealthDeviceDeviceIdPostRequest.to_json())

# convert the object into a dict
v1_backbone_health_device_device_id_post_request_dict = v1_backbone_health_device_device_id_post_request_instance.to_dict()
# create an instance of V1BackboneHealthDeviceDeviceIdPostRequest from a dict
v1_backbone_health_device_device_id_post_request_from_dict = V1BackboneHealthDeviceDeviceIdPostRequest.from_dict(v1_backbone_health_device_device_id_post_request_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


