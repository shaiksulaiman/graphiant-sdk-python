# V1AppsDeviceDeviceIdTopPostResponse


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**apps_utilization** | [**List[IpfixAppUtilizationSummary]**](IpfixAppUtilizationSummary.md) |  | [optional] 
**total_count** | **int** |  | [optional] 

## Example

```python
from graphiant_sdk.models.v1_apps_device_device_id_top_post_response import V1AppsDeviceDeviceIdTopPostResponse

# TODO update the JSON string below
json = "{}"
# create an instance of V1AppsDeviceDeviceIdTopPostResponse from a JSON string
v1_apps_device_device_id_top_post_response_instance = V1AppsDeviceDeviceIdTopPostResponse.from_json(json)
# print the JSON string representation of the object
print(V1AppsDeviceDeviceIdTopPostResponse.to_json())

# convert the object into a dict
v1_apps_device_device_id_top_post_response_dict = v1_apps_device_device_id_top_post_response_instance.to_dict()
# create an instance of V1AppsDeviceDeviceIdTopPostResponse from a dict
v1_apps_device_device_id_top_post_response_from_dict = V1AppsDeviceDeviceIdTopPostResponse.from_dict(v1_apps_device_device_id_top_post_response_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


