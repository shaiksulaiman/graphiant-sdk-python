# AssuranceBucketAppIdentifier


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**app_name** | **str** |  | [optional] 
**bucket_id** | **str** |  | [optional] 

## Example

```python
from graphiant_sdk.models.assurance_bucket_app_identifier import AssuranceBucketAppIdentifier

# TODO update the JSON string below
json = "{}"
# create an instance of AssuranceBucketAppIdentifier from a JSON string
assurance_bucket_app_identifier_instance = AssuranceBucketAppIdentifier.from_json(json)
# print the JSON string representation of the object
print(AssuranceBucketAppIdentifier.to_json())

# convert the object into a dict
assurance_bucket_app_identifier_dict = assurance_bucket_app_identifier_instance.to_dict()
# create an instance of AssuranceBucketAppIdentifier from a dict
assurance_bucket_app_identifier_from_dict = AssuranceBucketAppIdentifier.from_dict(assurance_bucket_app_identifier_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


