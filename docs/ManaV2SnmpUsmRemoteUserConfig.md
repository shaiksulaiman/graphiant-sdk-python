# ManaV2SnmpUsmRemoteUserConfig


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**auth_loc_key** | **str** |  | [optional] 
**auth_protocol** | **str** |  | [optional] 
**encryption_loc_key** | **str** |  | [optional] 
**encryption_protocol** | **str** |  | [optional] 
**name** | **str** |  | [optional] 

## Example

```python
from graphiant_sdk.models.mana_v2_snmp_usm_remote_user_config import ManaV2SnmpUsmRemoteUserConfig

# TODO update the JSON string below
json = "{}"
# create an instance of ManaV2SnmpUsmRemoteUserConfig from a JSON string
mana_v2_snmp_usm_remote_user_config_instance = ManaV2SnmpUsmRemoteUserConfig.from_json(json)
# print the JSON string representation of the object
print(ManaV2SnmpUsmRemoteUserConfig.to_json())

# convert the object into a dict
mana_v2_snmp_usm_remote_user_config_dict = mana_v2_snmp_usm_remote_user_config_instance.to_dict()
# create an instance of ManaV2SnmpUsmRemoteUserConfig from a dict
mana_v2_snmp_usm_remote_user_config_from_dict = ManaV2SnmpUsmRemoteUserConfig.from_dict(mana_v2_snmp_usm_remote_user_config_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


