# ManaV2SnmpTarget


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**community** | **str** |  | [optional] 
**id** | **int** |  | [optional] 
**name** | **str** |  | [optional] 
**notify_filter_profile** | **str** |  | [optional] 
**notify_type** | **str** |  | [optional] 
**source_ip** | **str** |  | [optional] 
**target_ip** | **str** |  | [optional] 
**target_type** | **str** |  | [optional] 
**usm_security_level** | **str** |  | [optional] 
**usm_user_name** | **str** |  | [optional] 
**vrf_name** | **str** |  | [optional] 

## Example

```python
from graphiant_sdk.models.mana_v2_snmp_target import ManaV2SnmpTarget

# TODO update the JSON string below
json = "{}"
# create an instance of ManaV2SnmpTarget from a JSON string
mana_v2_snmp_target_instance = ManaV2SnmpTarget.from_json(json)
# print the JSON string representation of the object
print(ManaV2SnmpTarget.to_json())

# convert the object into a dict
mana_v2_snmp_target_dict = mana_v2_snmp_target_instance.to_dict()
# create an instance of ManaV2SnmpTarget from a dict
mana_v2_snmp_target_from_dict = ManaV2SnmpTarget.from_dict(mana_v2_snmp_target_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


