# ManaV2SyslogCollectorConfig


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**enabled** | **bool** |  | [optional] 
**global_id** | **int** |  | [optional] 
**host** | **str** |  | [optional] 
**interface_name** | **str** |  | [optional] 
**is_global_sync** | **bool** |  | [optional] 
**name** | **str** |  | [optional] 
**port** | **int** |  | [optional] 
**severity** | **str** |  | [optional] 
**transport** | **str** |  | [optional] 
**vrf_id** | **int** |  | [optional] 

## Example

```python
from graphiant_sdk.models.mana_v2_syslog_collector_config import ManaV2SyslogCollectorConfig

# TODO update the JSON string below
json = "{}"
# create an instance of ManaV2SyslogCollectorConfig from a JSON string
mana_v2_syslog_collector_config_instance = ManaV2SyslogCollectorConfig.from_json(json)
# print the JSON string representation of the object
print(ManaV2SyslogCollectorConfig.to_json())

# convert the object into a dict
mana_v2_syslog_collector_config_dict = mana_v2_syslog_collector_config_instance.to_dict()
# create an instance of ManaV2SyslogCollectorConfig from a dict
mana_v2_syslog_collector_config_from_dict = ManaV2SyslogCollectorConfig.from_dict(mana_v2_syslog_collector_config_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


