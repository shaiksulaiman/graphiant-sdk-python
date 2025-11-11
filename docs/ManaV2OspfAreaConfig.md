# ManaV2OspfAreaConfig


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**area_id** | **str** |  | [optional] 
**interfaces** | [**Dict[str, ManaV2NullableOspfInterfaceConfig]**](ManaV2NullableOspfInterfaceConfig.md) |  | [optional] 
**name** | **str** |  | [optional] 
**type** | **str** |  | [optional] 

## Example

```python
from graphiant_sdk.models.mana_v2_ospf_area_config import ManaV2OspfAreaConfig

# TODO update the JSON string below
json = "{}"
# create an instance of ManaV2OspfAreaConfig from a JSON string
mana_v2_ospf_area_config_instance = ManaV2OspfAreaConfig.from_json(json)
# print the JSON string representation of the object
print(ManaV2OspfAreaConfig.to_json())

# convert the object into a dict
mana_v2_ospf_area_config_dict = mana_v2_ospf_area_config_instance.to_dict()
# create an instance of ManaV2OspfAreaConfig from a dict
mana_v2_ospf_area_config_from_dict = ManaV2OspfAreaConfig.from_dict(mana_v2_ospf_area_config_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


