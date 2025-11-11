# ManaV2Snmp


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**communities** | [**List[ManaV2SnmpCommunity]**](ManaV2SnmpCommunity.md) |  | [optional] 
**engine_enable_authen_traps** | **bool** |  | [optional] 
**engine_enable_high_memory_traps** | **bool** |  | [optional] 
**engine_enable_high_cpu_traps** | **bool** |  | [optional] 
**engine_enable_local_acess_v4** | **bool** |  | [optional] 
**engine_enable_local_acess_v6** | **bool** |  | [optional] 
**engine_enable_user_hints** | **bool** |  | [optional] 
**engine_enable_user_validation** | **bool** |  | [optional] 
**engine_enabled** | **bool** |  | [optional] 
**engine_endpoints** | [**List[ManaV2SnmpEngineEndpoint]**](ManaV2SnmpEngineEndpoint.md) |  | [optional] 
**engine_id_admin_octets** | **str** |  | [optional] 
**engine_id_admin_text** | **str** |  | [optional] 
**engine_id_ipv4** | **str** |  | [optional] 
**engine_id_ipv6** | **str** |  | [optional] 
**engine_id_mac** | **str** |  | [optional] 
**engine_id_raw** | **str** |  | [optional] 
**error_message** | **str** |  | [optional] 
**global_id** | **int** |  | [optional] 
**id** | **int** |  | [optional] 
**name** | **str** |  | [optional] 
**notify_filter_profiles** | [**List[ManaV2SnmpNotifyFilterProfile]**](ManaV2SnmpNotifyFilterProfile.md) |  | [optional] 
**snmp_version** | **str** |  | [optional] 
**status** | **str** |  | [optional] 
**targets** | [**List[ManaV2SnmpTarget]**](ManaV2SnmpTarget.md) |  | [optional] 
**usm_local_users** | [**List[ManaV2SnmpUsmLocalUser]**](ManaV2SnmpUsmLocalUser.md) |  | [optional] 
**usm_remote_users** | [**List[ManaV2SnmpUsmRemoteUser]**](ManaV2SnmpUsmRemoteUser.md) |  | [optional] 
**v2c_enabled** | **bool** |  | [optional] 
**v3_enabled** | **bool** |  | [optional] 
**vacm_groups** | [**List[ManaV2SnmpVacmGroup]**](ManaV2SnmpVacmGroup.md) |  | [optional] 

## Example

```python
from graphiant_sdk.models.mana_v2_snmp import ManaV2Snmp

# TODO update the JSON string below
json = "{}"
# create an instance of ManaV2Snmp from a JSON string
mana_v2_snmp_instance = ManaV2Snmp.from_json(json)
# print the JSON string representation of the object
print(ManaV2Snmp.to_json())

# convert the object into a dict
mana_v2_snmp_dict = mana_v2_snmp_instance.to_dict()
# create an instance of ManaV2Snmp from a dict
mana_v2_snmp_from_dict = ManaV2Snmp.from_dict(mana_v2_snmp_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


