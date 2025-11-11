# ManaV2DeviceFilter


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**hostname** | **str** |  | [optional] 
**list** | **str** |  | [optional] 
**role** | **str** |  | [optional] 
**site_id** | **int** |  | [optional] 

## Example

```python
from graphiant_sdk.models.mana_v2_device_filter import ManaV2DeviceFilter

# TODO update the JSON string below
json = "{}"
# create an instance of ManaV2DeviceFilter from a JSON string
mana_v2_device_filter_instance = ManaV2DeviceFilter.from_json(json)
# print the JSON string representation of the object
print(ManaV2DeviceFilter.to_json())

# convert the object into a dict
mana_v2_device_filter_dict = mana_v2_device_filter_instance.to_dict()
# create an instance of ManaV2DeviceFilter from a dict
mana_v2_device_filter_from_dict = ManaV2DeviceFilter.from_dict(mana_v2_device_filter_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


