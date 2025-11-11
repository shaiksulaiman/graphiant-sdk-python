# ManaV2SnmpVacmGroupAccessConfig


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**context** | **str** |  | [optional] 
**context_match** | **str** |  | [optional] 
**name** | **str** |  | [optional] 
**read_view** | **str** |  | [optional] 
**security_level** | **str** |  | [optional] 
**security_model** | **str** |  | [optional] 
**write_view** | **str** |  | [optional] 

## Example

```python
from graphiant_sdk.models.mana_v2_snmp_vacm_group_access_config import ManaV2SnmpVacmGroupAccessConfig

# TODO update the JSON string below
json = "{}"
# create an instance of ManaV2SnmpVacmGroupAccessConfig from a JSON string
mana_v2_snmp_vacm_group_access_config_instance = ManaV2SnmpVacmGroupAccessConfig.from_json(json)
# print the JSON string representation of the object
print(ManaV2SnmpVacmGroupAccessConfig.to_json())

# convert the object into a dict
mana_v2_snmp_vacm_group_access_config_dict = mana_v2_snmp_vacm_group_access_config_instance.to_dict()
# create an instance of ManaV2SnmpVacmGroupAccessConfig from a dict
mana_v2_snmp_vacm_group_access_config_from_dict = ManaV2SnmpVacmGroupAccessConfig.from_dict(mana_v2_snmp_vacm_group_access_config_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


