# ManaV2SnmpVacmGroupMember


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**id** | **int** |  | [optional] 
**security_model** | **str** |  | [optional] 
**security_name** | **str** |  | [optional] 
**snmp_community** | **str** |  | [optional] 
**type** | **str** |  | [optional] 

## Example

```python
from graphiant_sdk.models.mana_v2_snmp_vacm_group_member import ManaV2SnmpVacmGroupMember

# TODO update the JSON string below
json = "{}"
# create an instance of ManaV2SnmpVacmGroupMember from a JSON string
mana_v2_snmp_vacm_group_member_instance = ManaV2SnmpVacmGroupMember.from_json(json)
# print the JSON string representation of the object
print(ManaV2SnmpVacmGroupMember.to_json())

# convert the object into a dict
mana_v2_snmp_vacm_group_member_dict = mana_v2_snmp_vacm_group_member_instance.to_dict()
# create an instance of ManaV2SnmpVacmGroupMember from a dict
mana_v2_snmp_vacm_group_member_from_dict = ManaV2SnmpVacmGroupMember.from_dict(mana_v2_snmp_vacm_group_member_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


