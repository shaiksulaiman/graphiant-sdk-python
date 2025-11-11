# ManaV2SyslogCollector


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**destination_host** | **str** |  | [optional] 
**destination_port** | **int** |  | [optional] 
**enabled** | **bool** |  | [optional] 
**error_message** | **str** |  | [optional] 
**global_id** | **int** |  | [optional] 
**id** | **int** |  | [optional] 
**name** | **str** |  | [optional] 
**severity** | **str** |  | [optional] 
**source_interface** | **str** |  | [optional] 
**status** | **str** |  | [optional] 
**transport** | **str** |  | [optional] 
**vrf_id** | **int** |  | [optional] 
**vrf_name** | **str** |  | [optional] 

## Example

```python
from graphiant_sdk.models.mana_v2_syslog_collector import ManaV2SyslogCollector

# TODO update the JSON string below
json = "{}"
# create an instance of ManaV2SyslogCollector from a JSON string
mana_v2_syslog_collector_instance = ManaV2SyslogCollector.from_json(json)
# print the JSON string representation of the object
print(ManaV2SyslogCollector.to_json())

# convert the object into a dict
mana_v2_syslog_collector_dict = mana_v2_syslog_collector_instance.to_dict()
# create an instance of ManaV2SyslogCollector from a dict
mana_v2_syslog_collector_from_dict = ManaV2SyslogCollector.from_dict(mana_v2_syslog_collector_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


