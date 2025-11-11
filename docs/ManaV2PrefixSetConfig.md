# ManaV2PrefixSetConfig


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**description** | **str** |  | [optional] 
**entries** | [**Dict[str, ManaV2PrefixSetConfigNullableEntry]**](ManaV2PrefixSetConfigNullableEntry.md) |  | [optional] 
**global_id** | **int** |  | [optional] 
**is_global_sync** | **bool** |  | [optional] 
**mode** | **str** |  | [optional] 
**name** | **str** |  | [optional] 

## Example

```python
from graphiant_sdk.models.mana_v2_prefix_set_config import ManaV2PrefixSetConfig

# TODO update the JSON string below
json = "{}"
# create an instance of ManaV2PrefixSetConfig from a JSON string
mana_v2_prefix_set_config_instance = ManaV2PrefixSetConfig.from_json(json)
# print the JSON string representation of the object
print(ManaV2PrefixSetConfig.to_json())

# convert the object into a dict
mana_v2_prefix_set_config_dict = mana_v2_prefix_set_config_instance.to_dict()
# create an instance of ManaV2PrefixSetConfig from a dict
mana_v2_prefix_set_config_from_dict = ManaV2PrefixSetConfig.from_dict(mana_v2_prefix_set_config_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


