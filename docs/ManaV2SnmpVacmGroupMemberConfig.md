# ManaV2SnmpVacmGroupMemberConfig


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**community** | **str** |  | [optional] 
**security_model** | **str** |  | [optional] 
**security_name** | **str** |  | [optional] 
**type** | **str** |  | [optional] 

## Example

```python
from graphiant_sdk.models.mana_v2_snmp_vacm_group_member_config import ManaV2SnmpVacmGroupMemberConfig

# TODO update the JSON string below
json = "{}"
# create an instance of ManaV2SnmpVacmGroupMemberConfig from a JSON string
mana_v2_snmp_vacm_group_member_config_instance = ManaV2SnmpVacmGroupMemberConfig.from_json(json)
# print the JSON string representation of the object
print(ManaV2SnmpVacmGroupMemberConfig.to_json())

# convert the object into a dict
mana_v2_snmp_vacm_group_member_config_dict = mana_v2_snmp_vacm_group_member_config_instance.to_dict()
# create an instance of ManaV2SnmpVacmGroupMemberConfig from a dict
mana_v2_snmp_vacm_group_member_config_from_dict = ManaV2SnmpVacmGroupMemberConfig.from_dict(mana_v2_snmp_vacm_group_member_config_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


