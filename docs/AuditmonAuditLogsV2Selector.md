# AuditmonAuditLogsV2Selector


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**categories** | **List[str]** |  | [optional] 
**entities** | [**List[AuditActivityItem]**](AuditActivityItem.md) |  | [optional] 
**job_types** | **List[str]** |  | [optional] 
**targets** | [**List[AuditActivityItem]**](AuditActivityItem.md) |  | [optional] 
**users** | **List[str]** |  | [optional] 

## Example

```python
from graphiant_sdk.models.auditmon_audit_logs_v2_selector import AuditmonAuditLogsV2Selector

# TODO update the JSON string below
json = "{}"
# create an instance of AuditmonAuditLogsV2Selector from a JSON string
auditmon_audit_logs_v2_selector_instance = AuditmonAuditLogsV2Selector.from_json(json)
# print the JSON string representation of the object
print(AuditmonAuditLogsV2Selector.to_json())

# convert the object into a dict
auditmon_audit_logs_v2_selector_dict = auditmon_audit_logs_v2_selector_instance.to_dict()
# create an instance of AuditmonAuditLogsV2Selector from a dict
auditmon_audit_logs_v2_selector_from_dict = AuditmonAuditLogsV2Selector.from_dict(auditmon_audit_logs_v2_selector_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


