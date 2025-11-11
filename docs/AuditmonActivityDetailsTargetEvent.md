# AuditmonActivityDetailsTargetEvent


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**state** | **str** |  | [optional] 
**state_id** | **int** |  | [optional] 
**trace_session_id** | **str** |  | [optional] 
**ts** | [**GoogleProtobufTimestamp**](GoogleProtobufTimestamp.md) |  | [optional] 

## Example

```python
from graphiant_sdk.models.auditmon_activity_details_target_event import AuditmonActivityDetailsTargetEvent

# TODO update the JSON string below
json = "{}"
# create an instance of AuditmonActivityDetailsTargetEvent from a JSON string
auditmon_activity_details_target_event_instance = AuditmonActivityDetailsTargetEvent.from_json(json)
# print the JSON string representation of the object
print(AuditmonActivityDetailsTargetEvent.to_json())

# convert the object into a dict
auditmon_activity_details_target_event_dict = auditmon_activity_details_target_event_instance.to_dict()
# create an instance of AuditmonActivityDetailsTargetEvent from a dict
auditmon_activity_details_target_event_from_dict = AuditmonActivityDetailsTargetEvent.from_dict(auditmon_activity_details_target_event_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


