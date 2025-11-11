# ManaV2SnmpNotifyFilterProfileConfig


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**include_exclude_list** | [**Dict[str, ManaV2NotifyFilterProfileIncludeConfig]**](ManaV2NotifyFilterProfileIncludeConfig.md) |  | [optional] 
**name** | **str** |  | [optional] 

## Example

```python
from graphiant_sdk.models.mana_v2_snmp_notify_filter_profile_config import ManaV2SnmpNotifyFilterProfileConfig

# TODO update the JSON string below
json = "{}"
# create an instance of ManaV2SnmpNotifyFilterProfileConfig from a JSON string
mana_v2_snmp_notify_filter_profile_config_instance = ManaV2SnmpNotifyFilterProfileConfig.from_json(json)
# print the JSON string representation of the object
print(ManaV2SnmpNotifyFilterProfileConfig.to_json())

# convert the object into a dict
mana_v2_snmp_notify_filter_profile_config_dict = mana_v2_snmp_notify_filter_profile_config_instance.to_dict()
# create an instance of ManaV2SnmpNotifyFilterProfileConfig from a dict
mana_v2_snmp_notify_filter_profile_config_from_dict = ManaV2SnmpNotifyFilterProfileConfig.from_dict(mana_v2_snmp_notify_filter_profile_config_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


