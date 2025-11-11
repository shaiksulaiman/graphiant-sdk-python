# V1DevicesDeviceIdDraftGetResponse


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**draft** | [**ManaV2ManaConfiguration**](ManaV2ManaConfiguration.md) |  | [optional] 

## Example

```python
from graphiant_sdk.models.v1_devices_device_id_draft_get_response import V1DevicesDeviceIdDraftGetResponse

# TODO update the JSON string below
json = "{}"
# create an instance of V1DevicesDeviceIdDraftGetResponse from a JSON string
v1_devices_device_id_draft_get_response_instance = V1DevicesDeviceIdDraftGetResponse.from_json(json)
# print the JSON string representation of the object
print(V1DevicesDeviceIdDraftGetResponse.to_json())

# convert the object into a dict
v1_devices_device_id_draft_get_response_dict = v1_devices_device_id_draft_get_response_instance.to_dict()
# create an instance of V1DevicesDeviceIdDraftGetResponse from a dict
v1_devices_device_id_draft_get_response_from_dict = V1DevicesDeviceIdDraftGetResponse.from_dict(v1_devices_device_id_draft_get_response_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


