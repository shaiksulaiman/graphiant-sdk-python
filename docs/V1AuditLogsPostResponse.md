# V1AuditLogsPostResponse


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**cursor_ref** | **str** |  | [optional] 
**histogram** | [**List[AuditmonHistogram]**](AuditmonHistogram.md) |  | [optional] 
**logs** | [**List[AuditAuditEntry]**](AuditAuditEntry.md) |  | [optional] 
**total_logs** | **int** |  | [optional] 

## Example

```python
from graphiant_sdk.models.v1_audit_logs_post_response import V1AuditLogsPostResponse

# TODO update the JSON string below
json = "{}"
# create an instance of V1AuditLogsPostResponse from a JSON string
v1_audit_logs_post_response_instance = V1AuditLogsPostResponse.from_json(json)
# print the JSON string representation of the object
print(V1AuditLogsPostResponse.to_json())

# convert the object into a dict
v1_audit_logs_post_response_dict = v1_audit_logs_post_response_instance.to_dict()
# create an instance of V1AuditLogsPostResponse from a dict
v1_audit_logs_post_response_from_dict = V1AuditLogsPostResponse.from_dict(v1_audit_logs_post_response_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


