# AuditmonActivityDetails


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**action** | **str** |  | [optional] 
**attributes** | [**List[AuditActivityItem]**](AuditActivityItem.md) |  | [optional] 
**category** | **str** |  | [optional] 
**disable_auto_timeout** | **bool** |  | [optional] 
**end_ts** | [**GoogleProtobufTimestamp**](GoogleProtobufTimestamp.md) |  | [optional] 
**enterprise_id** | **int** |  | [optional] 
**id** | **str** |  | [optional] 
**initiator_type** | **str** |  | [optional] 
**job_entities** | [**List[AuditActivityItem]**](AuditActivityItem.md) |  | [optional] 
**job_type** | **str** |  | [optional] 
**original_enterprise_id** | **int** |  | [optional] 
**start_ts** | [**GoogleProtobufTimestamp**](GoogleProtobufTimestamp.md) |  | [optional] 
**status** | **str** |  | [optional] 
**targets** | [**List[AuditmonActivityDetailsTarget]**](AuditmonActivityDetailsTarget.md) |  | [optional] 
**trace_session_id** | **str** |  | [optional] 
**usage** | **str** |  | [optional] 
**user** | **str** |  | [optional] 
**user_id** | **str** |  | [optional] 

## Example

```python
from graphiant_sdk.models.auditmon_activity_details import AuditmonActivityDetails

# TODO update the JSON string below
json = "{}"
# create an instance of AuditmonActivityDetails from a JSON string
auditmon_activity_details_instance = AuditmonActivityDetails.from_json(json)
# print the JSON string representation of the object
print(AuditmonActivityDetails.to_json())

# convert the object into a dict
auditmon_activity_details_dict = auditmon_activity_details_instance.to_dict()
# create an instance of AuditmonActivityDetails from a dict
auditmon_activity_details_from_dict = AuditmonActivityDetails.from_dict(auditmon_activity_details_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


