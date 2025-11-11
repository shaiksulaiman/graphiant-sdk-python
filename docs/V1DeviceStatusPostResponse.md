# V1DeviceStatusPostResponse


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**mappings** | [**List[PokedexDeviceMappingInfo]**](PokedexDeviceMappingInfo.md) |  | [optional] 

## Example

```python
from graphiant_sdk.models.v1_device_status_post_response import V1DeviceStatusPostResponse

# TODO update the JSON string below
json = "{}"
# create an instance of V1DeviceStatusPostResponse from a JSON string
v1_device_status_post_response_instance = V1DeviceStatusPostResponse.from_json(json)
# print the JSON string representation of the object
print(V1DeviceStatusPostResponse.to_json())

# convert the object into a dict
v1_device_status_post_response_dict = v1_device_status_post_response_instance.to_dict()
# create an instance of V1DeviceStatusPostResponse from a dict
v1_device_status_post_response_from_dict = V1DeviceStatusPostResponse.from_dict(v1_device_status_post_response_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


