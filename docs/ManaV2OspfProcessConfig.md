# ManaV2OspfProcessConfig


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**address_families** | **List[str]** |  | [optional] 
**admin_distance** | [**ManaV2NullableOspfAdminDistanceValue**](ManaV2NullableOspfAdminDistanceValue.md) |  | [optional] 
**areas** | [**Dict[str, ManaV2NullableOspfAreaConfig]**](ManaV2NullableOspfAreaConfig.md) |  | [optional] 
**auto** | **bool** |  | [optional] 
**default_originate** | **str** |  | [optional] 
**manual** | **str** |  | [optional] 
**name** | **str** |  | [optional] 
**redistribution** | [**Dict[str, ManaV2NullableOspfRedistributeProtocolConfig]**](ManaV2NullableOspfRedistributeProtocolConfig.md) |  | [optional] 

## Example

```python
from graphiant_sdk.models.mana_v2_ospf_process_config import ManaV2OspfProcessConfig

# TODO update the JSON string below
json = "{}"
# create an instance of ManaV2OspfProcessConfig from a JSON string
mana_v2_ospf_process_config_instance = ManaV2OspfProcessConfig.from_json(json)
# print the JSON string representation of the object
print(ManaV2OspfProcessConfig.to_json())

# convert the object into a dict
mana_v2_ospf_process_config_dict = mana_v2_ospf_process_config_instance.to_dict()
# create an instance of ManaV2OspfProcessConfig from a dict
mana_v2_ospf_process_config_from_dict = ManaV2OspfProcessConfig.from_dict(mana_v2_ospf_process_config_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


