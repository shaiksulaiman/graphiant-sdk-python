# ManaV2ExtranetDeviceStatus


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**device_id** | **int** |  | [optional] 
**device_name** | **str** |  | [optional] 
**site_name** | **str** |  | [optional] 
**status** | **str** |  | [optional] 

## Example

```python
from graphiant_sdk.models.mana_v2_extranet_device_status import ManaV2ExtranetDeviceStatus

# TODO update the JSON string below
json = "{}"
# create an instance of ManaV2ExtranetDeviceStatus from a JSON string
mana_v2_extranet_device_status_instance = ManaV2ExtranetDeviceStatus.from_json(json)
# print the JSON string representation of the object
print(ManaV2ExtranetDeviceStatus.to_json())

# convert the object into a dict
mana_v2_extranet_device_status_dict = mana_v2_extranet_device_status_instance.to_dict()
# create an instance of ManaV2ExtranetDeviceStatus from a dict
mana_v2_extranet_device_status_from_dict = ManaV2ExtranetDeviceStatus.from_dict(mana_v2_extranet_device_status_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


