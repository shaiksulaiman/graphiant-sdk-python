# V2AuditLogsPostResponse


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**cursor_ref** | **str** |  | [optional] 
**logs** | [**List[AuditmonAuditLog]**](AuditmonAuditLog.md) |  | [optional] 
**total_logs** | **int** |  | [optional] 

## Example

```python
from graphiant_sdk.models.v2_audit_logs_post_response import V2AuditLogsPostResponse

# TODO update the JSON string below
json = "{}"
# create an instance of V2AuditLogsPostResponse from a JSON string
v2_audit_logs_post_response_instance = V2AuditLogsPostResponse.from_json(json)
# print the JSON string representation of the object
print(V2AuditLogsPostResponse.to_json())

# convert the object into a dict
v2_audit_logs_post_response_dict = v2_audit_logs_post_response_instance.to_dict()
# create an instance of V2AuditLogsPostResponse from a dict
v2_audit_logs_post_response_from_dict = V2AuditLogsPostResponse.from_dict(v2_audit_logs_post_response_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


