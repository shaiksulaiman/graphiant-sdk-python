# V1GlobalDeviceStatusGetResponse


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**statuses** | [**List[ManaV2GlobalObjectDeviceStatus]**](ManaV2GlobalObjectDeviceStatus.md) |  | [optional] 

## Example

```python
from graphiant_sdk.models.v1_global_device_status_get_response import V1GlobalDeviceStatusGetResponse

# TODO update the JSON string below
json = "{}"
# create an instance of V1GlobalDeviceStatusGetResponse from a JSON string
v1_global_device_status_get_response_instance = V1GlobalDeviceStatusGetResponse.from_json(json)
# print the JSON string representation of the object
print(V1GlobalDeviceStatusGetResponse.to_json())

# convert the object into a dict
v1_global_device_status_get_response_dict = v1_global_device_status_get_response_instance.to_dict()
# create an instance of V1GlobalDeviceStatusGetResponse from a dict
v1_global_device_status_get_response_from_dict = V1GlobalDeviceStatusGetResponse.from_dict(v1_global_device_status_get_response_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


