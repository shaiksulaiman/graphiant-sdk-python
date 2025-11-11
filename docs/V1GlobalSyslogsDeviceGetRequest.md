# V1GlobalSyslogsDeviceGetRequest


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**device_id** | **int** |  | [optional] 

## Example

```python
from graphiant_sdk.models.v1_global_syslogs_device_get_request import V1GlobalSyslogsDeviceGetRequest

# TODO update the JSON string below
json = "{}"
# create an instance of V1GlobalSyslogsDeviceGetRequest from a JSON string
v1_global_syslogs_device_get_request_instance = V1GlobalSyslogsDeviceGetRequest.from_json(json)
# print the JSON string representation of the object
print(V1GlobalSyslogsDeviceGetRequest.to_json())

# convert the object into a dict
v1_global_syslogs_device_get_request_dict = v1_global_syslogs_device_get_request_instance.to_dict()
# create an instance of V1GlobalSyslogsDeviceGetRequest from a dict
v1_global_syslogs_device_get_request_from_dict = V1GlobalSyslogsDeviceGetRequest.from_dict(v1_global_syslogs_device_get_request_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


