# AuditAuditEntry


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**activity** | **str** |  | [optional] 
**actor** | **str** |  | [optional] 
**category** | **str** |  | [optional] 
**end** | [**GoogleProtobufTimestamp**](GoogleProtobufTimestamp.md) |  | [optional] 
**failed_target_results** | [**List[AuditTargetResult]**](AuditTargetResult.md) |  | [optional] 
**info** | **str** |  | [optional] 
**reason** | **str** |  | [optional] 
**service** | **str** |  | [optional] 
**start** | [**GoogleProtobufTimestamp**](GoogleProtobufTimestamp.md) |  | [optional] 
**status** | **str** |  | [optional] 
**targets** | [**List[AuditTargetResult]**](AuditTargetResult.md) |  | [optional] 

## Example

```python
from graphiant_sdk.models.audit_audit_entry import AuditAuditEntry

# TODO update the JSON string below
json = "{}"
# create an instance of AuditAuditEntry from a JSON string
audit_audit_entry_instance = AuditAuditEntry.from_json(json)
# print the JSON string representation of the object
print(AuditAuditEntry.to_json())

# convert the object into a dict
audit_audit_entry_dict = audit_audit_entry_instance.to_dict()
# create an instance of AuditAuditEntry from a dict
audit_audit_entry_from_dict = AuditAuditEntry.from_dict(audit_audit_entry_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


