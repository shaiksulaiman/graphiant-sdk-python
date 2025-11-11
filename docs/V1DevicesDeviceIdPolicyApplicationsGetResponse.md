# V1DevicesDeviceIdPolicyApplicationsGetResponse


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**applications** | [**List[V1DevicesDeviceIdPolicyApplicationsGetResponseApplication]**](V1DevicesDeviceIdPolicyApplicationsGetResponseApplication.md) |  | [optional] 
**page_info** | [**CommonPageInfo**](CommonPageInfo.md) |  | [optional] 

## Example

```python
from graphiant_sdk.models.v1_devices_device_id_policy_applications_get_response import V1DevicesDeviceIdPolicyApplicationsGetResponse

# TODO update the JSON string below
json = "{}"
# create an instance of V1DevicesDeviceIdPolicyApplicationsGetResponse from a JSON string
v1_devices_device_id_policy_applications_get_response_instance = V1DevicesDeviceIdPolicyApplicationsGetResponse.from_json(json)
# print the JSON string representation of the object
print(V1DevicesDeviceIdPolicyApplicationsGetResponse.to_json())

# convert the object into a dict
v1_devices_device_id_policy_applications_get_response_dict = v1_devices_device_id_policy_applications_get_response_instance.to_dict()
# create an instance of V1DevicesDeviceIdPolicyApplicationsGetResponse from a dict
v1_devices_device_id_policy_applications_get_response_from_dict = V1DevicesDeviceIdPolicyApplicationsGetResponse.from_dict(v1_devices_device_id_policy_applications_get_response_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


