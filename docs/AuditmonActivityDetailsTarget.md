# AuditmonActivityDetailsTarget


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**detailed_failure_reason** | **str** |  | [optional] 
**end_ts** | [**GoogleProtobufTimestamp**](GoogleProtobufTimestamp.md) |  | [optional] 
**events** | [**List[AuditmonActivityDetailsTargetEvent]**](AuditmonActivityDetailsTargetEvent.md) |  | [optional] 
**failure_reason** | **str** |  | [optional] 
**ids** | [**List[AuditActivityItem]**](AuditActivityItem.md) |  | [optional] 
**start_ts** | [**GoogleProtobufTimestamp**](GoogleProtobufTimestamp.md) |  | [optional] 
**status** | **str** |  | [optional] 

## Example

```python
from graphiant_sdk.models.auditmon_activity_details_target import AuditmonActivityDetailsTarget

# TODO update the JSON string below
json = "{}"
# create an instance of AuditmonActivityDetailsTarget from a JSON string
auditmon_activity_details_target_instance = AuditmonActivityDetailsTarget.from_json(json)
# print the JSON string representation of the object
print(AuditmonActivityDetailsTarget.to_json())

# convert the object into a dict
auditmon_activity_details_target_dict = auditmon_activity_details_target_instance.to_dict()
# create an instance of AuditmonActivityDetailsTarget from a dict
auditmon_activity_details_target_from_dict = AuditmonActivityDetailsTarget.from_dict(auditmon_activity_details_target_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


