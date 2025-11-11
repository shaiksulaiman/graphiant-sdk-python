# ManaV2NullableSyslogCollectorConfig


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**target** | [**ManaV2SyslogCollectorConfig**](ManaV2SyslogCollectorConfig.md) |  | [optional] 

## Example

```python
from graphiant_sdk.models.mana_v2_nullable_syslog_collector_config import ManaV2NullableSyslogCollectorConfig

# TODO update the JSON string below
json = "{}"
# create an instance of ManaV2NullableSyslogCollectorConfig from a JSON string
mana_v2_nullable_syslog_collector_config_instance = ManaV2NullableSyslogCollectorConfig.from_json(json)
# print the JSON string representation of the object
print(ManaV2NullableSyslogCollectorConfig.to_json())

# convert the object into a dict
mana_v2_nullable_syslog_collector_config_dict = mana_v2_nullable_syslog_collector_config_instance.to_dict()
# create an instance of ManaV2NullableSyslogCollectorConfig from a dict
mana_v2_nullable_syslog_collector_config_from_dict = ManaV2NullableSyslogCollectorConfig.from_dict(mana_v2_nullable_syslog_collector_config_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


