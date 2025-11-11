# ManaV2GlobalObjectDeviceStatus


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**device_id** | **int** |  | [optional] 
**error_message** | **str** |  | [optional] 
**hostname** | **str** |  | [optional] 
**internal_state** | **str** |  | [optional] 
**site_name** | **str** |  | [optional] 
**status** | **str** |  | [optional] 
**status_since** | [**GoogleProtobufTimestamp**](GoogleProtobufTimestamp.md) |  | [optional] 

## Example

```python
from graphiant_sdk.models.mana_v2_global_object_device_status import ManaV2GlobalObjectDeviceStatus

# TODO update the JSON string below
json = "{}"
# create an instance of ManaV2GlobalObjectDeviceStatus from a JSON string
mana_v2_global_object_device_status_instance = ManaV2GlobalObjectDeviceStatus.from_json(json)
# print the JSON string representation of the object
print(ManaV2GlobalObjectDeviceStatus.to_json())

# convert the object into a dict
mana_v2_global_object_device_status_dict = mana_v2_global_object_device_status_instance.to_dict()
# create an instance of ManaV2GlobalObjectDeviceStatus from a dict
mana_v2_global_object_device_status_from_dict = ManaV2GlobalObjectDeviceStatus.from_dict(mana_v2_global_object_device_status_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


