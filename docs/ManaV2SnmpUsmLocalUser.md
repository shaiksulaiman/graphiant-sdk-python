# ManaV2SnmpUsmLocalUser


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**auth_passphrase** | **str** |  | [optional] 
**auth_protocol** | **str** |  | [optional] 
**encryption_passphrase** | **str** |  | [optional] 
**encryption_protocol** | **str** |  | [optional] 
**id** | **int** |  | [optional] 
**name** | **str** |  | [optional] 

## Example

```python
from graphiant_sdk.models.mana_v2_snmp_usm_local_user import ManaV2SnmpUsmLocalUser

# TODO update the JSON string below
json = "{}"
# create an instance of ManaV2SnmpUsmLocalUser from a JSON string
mana_v2_snmp_usm_local_user_instance = ManaV2SnmpUsmLocalUser.from_json(json)
# print the JSON string representation of the object
print(ManaV2SnmpUsmLocalUser.to_json())

# convert the object into a dict
mana_v2_snmp_usm_local_user_dict = mana_v2_snmp_usm_local_user_instance.to_dict()
# create an instance of ManaV2SnmpUsmLocalUser from a dict
mana_v2_snmp_usm_local_user_from_dict = ManaV2SnmpUsmLocalUser.from_dict(mana_v2_snmp_usm_local_user_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


