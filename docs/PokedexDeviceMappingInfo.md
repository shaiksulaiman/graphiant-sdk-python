# PokedexDeviceMappingInfo


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**connect_time** | [**GoogleProtobufTimestamp**](GoogleProtobufTimestamp.md) |  | [optional] 
**device_id** | **int** |  | [optional] 
**enterprise_id** | **int** |  | [optional] 
**hostname** | **str** |  | [optional] 
**ipaddress** | **str** |  | [optional] 
**tt_identity** | **str** |  | [optional] 

## Example

```python
from graphiant_sdk.models.pokedex_device_mapping_info import PokedexDeviceMappingInfo

# TODO update the JSON string below
json = "{}"
# create an instance of PokedexDeviceMappingInfo from a JSON string
pokedex_device_mapping_info_instance = PokedexDeviceMappingInfo.from_json(json)
# print the JSON string representation of the object
print(PokedexDeviceMappingInfo.to_json())

# convert the object into a dict
pokedex_device_mapping_info_dict = pokedex_device_mapping_info_instance.to_dict()
# create an instance of PokedexDeviceMappingInfo from a dict
pokedex_device_mapping_info_from_dict = PokedexDeviceMappingInfo.from_dict(pokedex_device_mapping_info_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


