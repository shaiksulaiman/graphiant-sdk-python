# AuditmonAuditLog


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**action** | **str** |  | [optional] 
**activity_id** | **str** |  | [optional] 
**category** | **str** |  | [optional] 
**entity** | [**AuditActivityItem**](AuditActivityItem.md) |  | [optional] 
**job_type** | **str** |  | [optional] 
**target** | [**AuditActivityItem**](AuditActivityItem.md) |  | [optional] 
**ts** | [**GoogleProtobufTimestamp**](GoogleProtobufTimestamp.md) |  | [optional] 
**user** | **str** |  | [optional] 

## Example

```python
from graphiant_sdk.models.auditmon_audit_log import AuditmonAuditLog

# TODO update the JSON string below
json = "{}"
# create an instance of AuditmonAuditLog from a JSON string
auditmon_audit_log_instance = AuditmonAuditLog.from_json(json)
# print the JSON string representation of the object
print(AuditmonAuditLog.to_json())

# convert the object into a dict
auditmon_audit_log_dict = auditmon_audit_log_instance.to_dict()
# create an instance of AuditmonAuditLog from a dict
auditmon_audit_log_from_dict = AuditmonAuditLog.from_dict(auditmon_audit_log_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


