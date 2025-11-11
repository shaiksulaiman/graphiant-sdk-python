# AuditTargetResult


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**reason** | **str** |  | [optional] 
**status** | **str** |  | [optional] 
**target** | [**AuditTarget**](AuditTarget.md) |  | [optional] 

## Example

```python
from graphiant_sdk.models.audit_target_result import AuditTargetResult

# TODO update the JSON string below
json = "{}"
# create an instance of AuditTargetResult from a JSON string
audit_target_result_instance = AuditTargetResult.from_json(json)
# print the JSON string representation of the object
print(AuditTargetResult.to_json())

# convert the object into a dict
audit_target_result_dict = audit_target_result_instance.to_dict()
# create an instance of AuditTargetResult from a dict
audit_target_result_from_dict = AuditTargetResult.from_dict(audit_target_result_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


