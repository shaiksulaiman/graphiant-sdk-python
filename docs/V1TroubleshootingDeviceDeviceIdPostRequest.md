# V1TroubleshootingDeviceDeviceIdPostRequest


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**time_window** | [**StatsmonTroubleshootingTimeWindow**](StatsmonTroubleshootingTimeWindow.md) |  | [optional] 

## Example

```python
from graphiant_sdk.models.v1_troubleshooting_device_device_id_post_request import V1TroubleshootingDeviceDeviceIdPostRequest

# TODO update the JSON string below
json = "{}"
# create an instance of V1TroubleshootingDeviceDeviceIdPostRequest from a JSON string
v1_troubleshooting_device_device_id_post_request_instance = V1TroubleshootingDeviceDeviceIdPostRequest.from_json(json)
# print the JSON string representation of the object
print(V1TroubleshootingDeviceDeviceIdPostRequest.to_json())

# convert the object into a dict
v1_troubleshooting_device_device_id_post_request_dict = v1_troubleshooting_device_device_id_post_request_instance.to_dict()
# create an instance of V1TroubleshootingDeviceDeviceIdPostRequest from a dict
v1_troubleshooting_device_device_id_post_request_from_dict = V1TroubleshootingDeviceDeviceIdPostRequest.from_dict(v1_troubleshooting_device_device_id_post_request_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


