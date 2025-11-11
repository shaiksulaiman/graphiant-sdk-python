# V1SoftwareRunningDetailsGetResponseDevice


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**device_id** | **int** |  | [optional] 
**enterprise_id** | **int** |  | [optional] 
**enterprise_name** | **str** |  | [optional] 
**hostname** | **str** |  | [optional] 

## Example

```python
from graphiant_sdk.models.v1_software_running_details_get_response_device import V1SoftwareRunningDetailsGetResponseDevice

# TODO update the JSON string below
json = "{}"
# create an instance of V1SoftwareRunningDetailsGetResponseDevice from a JSON string
v1_software_running_details_get_response_device_instance = V1SoftwareRunningDetailsGetResponseDevice.from_json(json)
# print the JSON string representation of the object
print(V1SoftwareRunningDetailsGetResponseDevice.to_json())

# convert the object into a dict
v1_software_running_details_get_response_device_dict = v1_software_running_details_get_response_device_instance.to_dict()
# create an instance of V1SoftwareRunningDetailsGetResponseDevice from a dict
v1_software_running_details_get_response_device_from_dict = V1SoftwareRunningDetailsGetResponseDevice.from_dict(v1_software_running_details_get_response_device_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


