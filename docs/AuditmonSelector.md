# AuditmonSelector


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**var_field** | **str** | Field to search | [optional] 
**values** | **List[str]** |  | [optional] 

## Example

```python
from graphiant_sdk.models.auditmon_selector import AuditmonSelector

# TODO update the JSON string below
json = "{}"
# create an instance of AuditmonSelector from a JSON string
auditmon_selector_instance = AuditmonSelector.from_json(json)
# print the JSON string representation of the object
print(AuditmonSelector.to_json())

# convert the object into a dict
auditmon_selector_dict = auditmon_selector_instance.to_dict()
# create an instance of AuditmonSelector from a dict
auditmon_selector_from_dict = AuditmonSelector.from_dict(auditmon_selector_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


