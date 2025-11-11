# SyslogmonSyslogsSelector


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**var_field** | **str** |  | [optional] 
**values** | **List[str]** |  | [optional] 

## Example

```python
from graphiant_sdk.models.syslogmon_syslogs_selector import SyslogmonSyslogsSelector

# TODO update the JSON string below
json = "{}"
# create an instance of SyslogmonSyslogsSelector from a JSON string
syslogmon_syslogs_selector_instance = SyslogmonSyslogsSelector.from_json(json)
# print the JSON string representation of the object
print(SyslogmonSyslogsSelector.to_json())

# convert the object into a dict
syslogmon_syslogs_selector_dict = syslogmon_syslogs_selector_instance.to_dict()
# create an instance of SyslogmonSyslogsSelector from a dict
syslogmon_syslogs_selector_from_dict = SyslogmonSyslogsSelector.from_dict(syslogmon_syslogs_selector_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


