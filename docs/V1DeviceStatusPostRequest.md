# V1DeviceStatusPostRequest


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**device_ids** | **List[int]** |  | [optional] 
**role** | **str** |  | [optional] 

## Example

```python
from graphiant_sdk.models.v1_device_status_post_request import V1DeviceStatusPostRequest

# TODO update the JSON string below
json = "{}"
# create an instance of V1DeviceStatusPostRequest from a JSON string
v1_device_status_post_request_instance = V1DeviceStatusPostRequest.from_json(json)
# print the JSON string representation of the object
print(V1DeviceStatusPostRequest.to_json())

# convert the object into a dict
v1_device_status_post_request_dict = v1_device_status_post_request_instance.to_dict()
# create an instance of V1DeviceStatusPostRequest from a dict
v1_device_status_post_request_from_dict = V1DeviceStatusPostRequest.from_dict(v1_device_status_post_request_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


