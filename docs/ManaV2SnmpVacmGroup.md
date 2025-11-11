# ManaV2SnmpVacmGroup


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**accesses** | [**List[ManaV2SnmpVacmGroupAccess]**](ManaV2SnmpVacmGroupAccess.md) |  | [optional] 
**group_members** | [**List[ManaV2SnmpVacmGroupMember]**](ManaV2SnmpVacmGroupMember.md) |  | [optional] 
**id** | **int** |  | [optional] 
**name** | **str** |  | [optional] 
**views** | [**List[ManaV2SnmpVacmView]**](ManaV2SnmpVacmView.md) |  | [optional] 

## Example

```python
from graphiant_sdk.models.mana_v2_snmp_vacm_group import ManaV2SnmpVacmGroup

# TODO update the JSON string below
json = "{}"
# create an instance of ManaV2SnmpVacmGroup from a JSON string
mana_v2_snmp_vacm_group_instance = ManaV2SnmpVacmGroup.from_json(json)
# print the JSON string representation of the object
print(ManaV2SnmpVacmGroup.to_json())

# convert the object into a dict
mana_v2_snmp_vacm_group_dict = mana_v2_snmp_vacm_group_instance.to_dict()
# create an instance of ManaV2SnmpVacmGroup from a dict
mana_v2_snmp_vacm_group_from_dict = ManaV2SnmpVacmGroup.from_dict(mana_v2_snmp_vacm_group_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


