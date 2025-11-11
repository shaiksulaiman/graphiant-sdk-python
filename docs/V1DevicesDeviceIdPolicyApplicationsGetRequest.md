# V1DevicesDeviceIdPolicyApplicationsGetRequest


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**page_request** | [**CommonPageRequest**](CommonPageRequest.md) |  | [optional] 

## Example

```python
from graphiant_sdk.models.v1_devices_device_id_policy_applications_get_request import V1DevicesDeviceIdPolicyApplicationsGetRequest

# TODO update the JSON string below
json = "{}"
# create an instance of V1DevicesDeviceIdPolicyApplicationsGetRequest from a JSON string
v1_devices_device_id_policy_applications_get_request_instance = V1DevicesDeviceIdPolicyApplicationsGetRequest.from_json(json)
# print the JSON string representation of the object
print(V1DevicesDeviceIdPolicyApplicationsGetRequest.to_json())

# convert the object into a dict
v1_devices_device_id_policy_applications_get_request_dict = v1_devices_device_id_policy_applications_get_request_instance.to_dict()
# create an instance of V1DevicesDeviceIdPolicyApplicationsGetRequest from a dict
v1_devices_device_id_policy_applications_get_request_from_dict = V1DevicesDeviceIdPolicyApplicationsGetRequest.from_dict(v1_devices_device_id_policy_applications_get_request_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


