# SyslogmonLog


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**device_id** | **int** |  | [optional] 
**facility** | **str** |  | [optional] 
**hostname** | **str** |  | [optional] 
**level** | **str** |  | [optional] 
**message** | **str** |  | [optional] 
**ts** | [**GoogleProtobufTimestamp**](GoogleProtobufTimestamp.md) |  | [optional] 

## Example

```python
from graphiant_sdk.models.syslogmon_log import SyslogmonLog

# TODO update the JSON string below
json = "{}"
# create an instance of SyslogmonLog from a JSON string
syslogmon_log_instance = SyslogmonLog.from_json(json)
# print the JSON string representation of the object
print(SyslogmonLog.to_json())

# convert the object into a dict
syslogmon_log_dict = syslogmon_log_instance.to_dict()
# create an instance of SyslogmonLog from a dict
syslogmon_log_from_dict = SyslogmonLog.from_dict(syslogmon_log_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


