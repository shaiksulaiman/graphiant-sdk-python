# ManaV2SnmpNotifyFilterProfile


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**id** | **int** |  | [optional] 
**include_exclude_list** | [**List[ManaV2NotifyFilterProfileInclude]**](ManaV2NotifyFilterProfileInclude.md) |  | [optional] 
**name** | **str** |  | [optional] 

## Example

```python
from graphiant_sdk.models.mana_v2_snmp_notify_filter_profile import ManaV2SnmpNotifyFilterProfile

# TODO update the JSON string below
json = "{}"
# create an instance of ManaV2SnmpNotifyFilterProfile from a JSON string
mana_v2_snmp_notify_filter_profile_instance = ManaV2SnmpNotifyFilterProfile.from_json(json)
# print the JSON string representation of the object
print(ManaV2SnmpNotifyFilterProfile.to_json())

# convert the object into a dict
mana_v2_snmp_notify_filter_profile_dict = mana_v2_snmp_notify_filter_profile_instance.to_dict()
# create an instance of ManaV2SnmpNotifyFilterProfile from a dict
mana_v2_snmp_notify_filter_profile_from_dict = ManaV2SnmpNotifyFilterProfile.from_dict(mana_v2_snmp_notify_filter_profile_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


