# ManaV2VacmGroupConfig


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**accesses** | [**Dict[str, ManaV2NullableSnmpVacmGroupAccessValue]**](ManaV2NullableSnmpVacmGroupAccessValue.md) |  | [optional] 
**members** | [**Dict[str, ManaV2NullableSnmpVacmGroupMemberValue]**](ManaV2NullableSnmpVacmGroupMemberValue.md) |  | [optional] 
**name** | **str** |  | [optional] 

## Example

```python
from graphiant_sdk.models.mana_v2_vacm_group_config import ManaV2VacmGroupConfig

# TODO update the JSON string below
json = "{}"
# create an instance of ManaV2VacmGroupConfig from a JSON string
mana_v2_vacm_group_config_instance = ManaV2VacmGroupConfig.from_json(json)
# print the JSON string representation of the object
print(ManaV2VacmGroupConfig.to_json())

# convert the object into a dict
mana_v2_vacm_group_config_dict = mana_v2_vacm_group_config_instance.to_dict()
# create an instance of ManaV2VacmGroupConfig from a dict
mana_v2_vacm_group_config_from_dict = ManaV2VacmGroupConfig.from_dict(mana_v2_vacm_group_config_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


