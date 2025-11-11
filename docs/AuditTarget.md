# AuditTarget


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**id** | **int** |  | [optional] 
**name** | **str** |  | [optional] 

## Example

```python
from graphiant_sdk.models.audit_target import AuditTarget

# TODO update the JSON string below
json = "{}"
# create an instance of AuditTarget from a JSON string
audit_target_instance = AuditTarget.from_json(json)
# print the JSON string representation of the object
print(AuditTarget.to_json())

# convert the object into a dict
audit_target_dict = audit_target_instance.to_dict()
# create an instance of AuditTarget from a dict
audit_target_from_dict = AuditTarget.from_dict(audit_target_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


