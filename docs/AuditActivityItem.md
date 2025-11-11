# AuditActivityItem


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**id** | **int** |  | [optional] 
**name** | **str** |  | [optional] 
**type** | **str** |  | [optional] 

## Example

```python
from graphiant_sdk.models.audit_activity_item import AuditActivityItem

# TODO update the JSON string below
json = "{}"
# create an instance of AuditActivityItem from a JSON string
audit_activity_item_instance = AuditActivityItem.from_json(json)
# print the JSON string representation of the object
print(AuditActivityItem.to_json())

# convert the object into a dict
audit_activity_item_dict = audit_activity_item_instance.to_dict()
# create an instance of AuditActivityItem from a dict
audit_activity_item_from_dict = AuditActivityItem.from_dict(audit_activity_item_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


