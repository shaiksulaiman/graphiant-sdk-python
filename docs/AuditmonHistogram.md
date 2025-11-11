# AuditmonHistogram


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**count** | **int** |  | [optional] 
**ts** | [**GoogleProtobufTimestamp**](GoogleProtobufTimestamp.md) |  | [optional] 

## Example

```python
from graphiant_sdk.models.auditmon_histogram import AuditmonHistogram

# TODO update the JSON string below
json = "{}"
# create an instance of AuditmonHistogram from a JSON string
auditmon_histogram_instance = AuditmonHistogram.from_json(json)
# print the JSON string representation of the object
print(AuditmonHistogram.to_json())

# convert the object into a dict
auditmon_histogram_dict = auditmon_histogram_instance.to_dict()
# create an instance of AuditmonHistogram from a dict
auditmon_histogram_from_dict = AuditmonHistogram.from_dict(auditmon_histogram_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


