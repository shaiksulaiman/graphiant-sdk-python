# V1DevicesGetRequest


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**device_filter** | [**ManaV2DeviceFilter**](ManaV2DeviceFilter.md) |  | [optional] 
**device_role** | **str** |  | [optional] 
**hostname** | **str** |  | [optional] 
**list** | **str** |  | [optional] 
**page_request** | [**CommonPageRequest**](CommonPageRequest.md) |  | [optional] 

## Example

```python
from graphiant_sdk.models.v1_devices_get_request import V1DevicesGetRequest

# TODO update the JSON string below
json = "{}"
# create an instance of V1DevicesGetRequest from a JSON string
v1_devices_get_request_instance = V1DevicesGetRequest.from_json(json)
# print the JSON string representation of the object
print(V1DevicesGetRequest.to_json())

# convert the object into a dict
v1_devices_get_request_dict = v1_devices_get_request_instance.to_dict()
# create an instance of V1DevicesGetRequest from a dict
v1_devices_get_request_from_dict = V1DevicesGetRequest.from_dict(v1_devices_get_request_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


