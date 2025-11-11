# AssuranceApplicationProfileSummary


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**bucket_summary_list** | [**List[AssuranceBucketSummary]**](AssuranceBucketSummary.md) |  | [optional] 

## Example

```python
from graphiant_sdk.models.assurance_application_profile_summary import AssuranceApplicationProfileSummary

# TODO update the JSON string below
json = "{}"
# create an instance of AssuranceApplicationProfileSummary from a JSON string
assurance_application_profile_summary_instance = AssuranceApplicationProfileSummary.from_json(json)
# print the JSON string representation of the object
print(AssuranceApplicationProfileSummary.to_json())

# convert the object into a dict
assurance_application_profile_summary_dict = assurance_application_profile_summary_instance.to_dict()
# create an instance of AssuranceApplicationProfileSummary from a dict
assurance_application_profile_summary_from_dict = AssuranceApplicationProfileSummary.from_dict(assurance_application_profile_summary_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


