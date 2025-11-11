# ManaV2SnmpVacmView


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**id** | **int** |  | [optional] 
**include_exclude** | [**List[ManaV2SnmpVacmViewInclude]**](ManaV2SnmpVacmViewInclude.md) |  | [optional] 
**name** | **str** |  | [optional] 

## Example

```python
from graphiant_sdk.models.mana_v2_snmp_vacm_view import ManaV2SnmpVacmView

# TODO update the JSON string below
json = "{}"
# create an instance of ManaV2SnmpVacmView from a JSON string
mana_v2_snmp_vacm_view_instance = ManaV2SnmpVacmView.from_json(json)
# print the JSON string representation of the object
print(ManaV2SnmpVacmView.to_json())

# convert the object into a dict
mana_v2_snmp_vacm_view_dict = mana_v2_snmp_vacm_view_instance.to_dict()
# create an instance of ManaV2SnmpVacmView from a dict
mana_v2_snmp_vacm_view_from_dict = ManaV2SnmpVacmView.from_dict(mana_v2_snmp_vacm_view_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


