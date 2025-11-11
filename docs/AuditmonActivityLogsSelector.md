# AuditmonActivityLogsSelector


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**device_ids** | **List[int]** |  | [optional] 
**id** | **str** |  | [optional] 
**in_progress** | **bool** |  | [optional] 
**job_entity** | [**AuditActivityItem**](AuditActivityItem.md) |  | [optional] 
**target_ids** | [**List[AuditActivityItem]**](AuditActivityItem.md) |  | [optional] 
**type** | **str** |  | [optional] 

## Example

```python
from graphiant_sdk.models.auditmon_activity_logs_selector import AuditmonActivityLogsSelector

# TODO update the JSON string below
json = "{}"
# create an instance of AuditmonActivityLogsSelector from a JSON string
auditmon_activity_logs_selector_instance = AuditmonActivityLogsSelector.from_json(json)
# print the JSON string representation of the object
print(AuditmonActivityLogsSelector.to_json())

# convert the object into a dict
auditmon_activity_logs_selector_dict = auditmon_activity_logs_selector_instance.to_dict()
# create an instance of AuditmonActivityLogsSelector from a dict
auditmon_activity_logs_selector_from_dict = AuditmonActivityLogsSelector.from_dict(auditmon_activity_logs_selector_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


