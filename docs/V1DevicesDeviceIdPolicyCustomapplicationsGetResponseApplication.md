# V1DevicesDeviceIdPolicyCustomapplicationsGetResponseApplication


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**app_id** | **int** |  | [optional] 
**description** | **str** |  | [optional] 
**kind** | **str** |  | [optional] 
**name** | **str** |  | [optional] 

## Example

```python
from graphiant_sdk.models.v1_devices_device_id_policy_customapplications_get_response_application import V1DevicesDeviceIdPolicyCustomapplicationsGetResponseApplication

# TODO update the JSON string below
json = "{}"
# create an instance of V1DevicesDeviceIdPolicyCustomapplicationsGetResponseApplication from a JSON string
v1_devices_device_id_policy_customapplications_get_response_application_instance = V1DevicesDeviceIdPolicyCustomapplicationsGetResponseApplication.from_json(json)
# print the JSON string representation of the object
print(V1DevicesDeviceIdPolicyCustomapplicationsGetResponseApplication.to_json())

# convert the object into a dict
v1_devices_device_id_policy_customapplications_get_response_application_dict = v1_devices_device_id_policy_customapplications_get_response_application_instance.to_dict()
# create an instance of V1DevicesDeviceIdPolicyCustomapplicationsGetResponseApplication from a dict
v1_devices_device_id_policy_customapplications_get_response_application_from_dict = V1DevicesDeviceIdPolicyCustomapplicationsGetResponseApplication.from_dict(v1_devices_device_id_policy_customapplications_get_response_application_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


