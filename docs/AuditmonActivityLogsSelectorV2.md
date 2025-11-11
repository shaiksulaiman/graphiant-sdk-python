# AuditmonActivityLogsSelectorV2


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**device_ids** | **List[int]** |  | [optional] 
**entities** | [**List[AuditActivityItem]**](AuditActivityItem.md) |  | [optional] 
**site_ids** | **List[int]** |  | [optional] 
**statuses** | **List[str]** |  | [optional] 
**types** | **List[str]** |  | [optional] 
**user_ids** | **List[str]** |  | [optional] 

## Example

```python
from graphiant_sdk.models.auditmon_activity_logs_selector_v2 import AuditmonActivityLogsSelectorV2

# TODO update the JSON string below
json = "{}"
# create an instance of AuditmonActivityLogsSelectorV2 from a JSON string
auditmon_activity_logs_selector_v2_instance = AuditmonActivityLogsSelectorV2.from_json(json)
# print the JSON string representation of the object
print(AuditmonActivityLogsSelectorV2.to_json())

# convert the object into a dict
auditmon_activity_logs_selector_v2_dict = auditmon_activity_logs_selector_v2_instance.to_dict()
# create an instance of AuditmonActivityLogsSelectorV2 from a dict
auditmon_activity_logs_selector_v2_from_dict = AuditmonActivityLogsSelectorV2.from_dict(auditmon_activity_logs_selector_v2_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


