# ManaV2SnmpVacmGroupAccess


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**context** | **str** |  | [optional] 
**group_context_match** | **str** |  | [optional] 
**id** | **int** |  | [optional] 
**name** | **str** |  | [optional] 
**read_view** | **str** |  | [optional] 
**security_level** | **str** |  | [optional] 
**write_view** | **str** |  | [optional] 

## Example

```python
from graphiant_sdk.models.mana_v2_snmp_vacm_group_access import ManaV2SnmpVacmGroupAccess

# TODO update the JSON string below
json = "{}"
# create an instance of ManaV2SnmpVacmGroupAccess from a JSON string
mana_v2_snmp_vacm_group_access_instance = ManaV2SnmpVacmGroupAccess.from_json(json)
# print the JSON string representation of the object
print(ManaV2SnmpVacmGroupAccess.to_json())

# convert the object into a dict
mana_v2_snmp_vacm_group_access_dict = mana_v2_snmp_vacm_group_access_instance.to_dict()
# create an instance of ManaV2SnmpVacmGroupAccess from a dict
mana_v2_snmp_vacm_group_access_from_dict = ManaV2SnmpVacmGroupAccess.from_dict(mana_v2_snmp_vacm_group_access_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


