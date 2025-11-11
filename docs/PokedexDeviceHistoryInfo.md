# PokedexDeviceHistoryInfo


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**device_id** | **int** |  | [optional] 
**enterprise_id** | **int** |  | [optional] 
**event** | **str** |  | [optional] 
**event_time** | [**GoogleProtobufTimestamp**](GoogleProtobufTimestamp.md) |  | [optional] 
**ipaddress** | **str** |  | [optional] 
**tt_identity** | **str** |  | [optional] 

## Example

```python
from graphiant_sdk.models.pokedex_device_history_info import PokedexDeviceHistoryInfo

# TODO update the JSON string below
json = "{}"
# create an instance of PokedexDeviceHistoryInfo from a JSON string
pokedex_device_history_info_instance = PokedexDeviceHistoryInfo.from_json(json)
# print the JSON string representation of the object
print(PokedexDeviceHistoryInfo.to_json())

# convert the object into a dict
pokedex_device_history_info_dict = pokedex_device_history_info_instance.to_dict()
# create an instance of PokedexDeviceHistoryInfo from a dict
pokedex_device_history_info_from_dict = PokedexDeviceHistoryInfo.from_dict(pokedex_device_history_info_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


