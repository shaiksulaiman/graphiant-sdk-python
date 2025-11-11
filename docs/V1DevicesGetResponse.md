# V1DevicesGetResponse


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**devices** | [**List[ManaV2Device]**](ManaV2Device.md) |  | [optional] 
**page_info** | [**CommonPageInfo**](CommonPageInfo.md) |  | [optional] 

## Example

```python
from graphiant_sdk.models.v1_devices_get_response import V1DevicesGetResponse

# TODO update the JSON string below
json = "{}"
# create an instance of V1DevicesGetResponse from a JSON string
v1_devices_get_response_instance = V1DevicesGetResponse.from_json(json)
# print the JSON string representation of the object
print(V1DevicesGetResponse.to_json())

# convert the object into a dict
v1_devices_get_response_dict = v1_devices_get_response_instance.to_dict()
# create an instance of V1DevicesGetResponse from a dict
v1_devices_get_response_from_dict = V1DevicesGetResponse.from_dict(v1_devices_get_response_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


