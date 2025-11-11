# ManaV2SnmpConfig


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**communities** | [**Dict[str, ManaV2NullableSnmpCommunityConfigValue]**](ManaV2NullableSnmpCommunityConfigValue.md) |  | [optional] 
**engine_authen_traps** | **bool** |  | [optional] 
**engine_enabled** | **bool** |  | [optional] 
**engine_endpoints** | [**Dict[str, ManaV2NullableSnmpEngineEndpointConfigValue]**](ManaV2NullableSnmpEngineEndpointConfigValue.md) |  | [optional] 
**engine_high_cpu_traps** | **bool** |  | [optional] 
**engine_high_memory_traps** | **bool** |  | [optional] 
**engine_id_admin_octets** | **str** |  | [optional] 
**engine_id_admin_text** | **str** |  | [optional] 
**engine_id_ipv4** | **str** |  | [optional] 
**engine_id_ipv6** | **str** |  | [optional] 
**engine_id_mac** | **str** |  | [optional] 
**engine_id_raw** | **str** |  | [optional] 
**engine_local_acess_v4** | **bool** |  | [optional] 
**engine_local_acess_v6** | **bool** |  | [optional] 
**engine_user_hints** | **bool** |  | [optional] 
**engine_user_validation** | **bool** |  | [optional] 
**global_id** | **int** |  | [optional] 
**is_global_sync** | **bool** |  | [optional] 
**name** | **str** |  | [optional] 
**notify_filter_profiles** | [**Dict[str, ManaV2NullableSnmpNotifyFilterProfileConfigValue]**](ManaV2NullableSnmpNotifyFilterProfileConfigValue.md) |  | [optional] 
**snmp_version** | **str** |  | [optional] 
**targets** | [**Dict[str, ManaV2NullableSnmpTargetConfigValue]**](ManaV2NullableSnmpTargetConfigValue.md) |  | [optional] 
**usm_local_users** | [**Dict[str, ManaV2NullableUsmLocalUserConfigValue]**](ManaV2NullableUsmLocalUserConfigValue.md) |  | [optional] 
**usm_remote_users** | [**Dict[str, ManaV2NullableUsmRemoteUserConfigValue]**](ManaV2NullableUsmRemoteUserConfigValue.md) |  | [optional] 
**v2c_enabled** | **bool** |  | [optional] 
**v3_enabled** | **bool** |  | [optional] 
**vacm_groups** | [**Dict[str, ManaV2NullableVacmGroupValue]**](ManaV2NullableVacmGroupValue.md) |  | [optional] 
**vacm_views** | [**Dict[str, ManaV2NullableSnmpVacmViewValue]**](ManaV2NullableSnmpVacmViewValue.md) |  | [optional] 

## Example

```python
from graphiant_sdk.models.mana_v2_snmp_config import ManaV2SnmpConfig

# TODO update the JSON string below
json = "{}"
# create an instance of ManaV2SnmpConfig from a JSON string
mana_v2_snmp_config_instance = ManaV2SnmpConfig.from_json(json)
# print the JSON string representation of the object
print(ManaV2SnmpConfig.to_json())

# convert the object into a dict
mana_v2_snmp_config_dict = mana_v2_snmp_config_instance.to_dict()
# create an instance of ManaV2SnmpConfig from a dict
mana_v2_snmp_config_from_dict = ManaV2SnmpConfig.from_dict(mana_v2_snmp_config_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


