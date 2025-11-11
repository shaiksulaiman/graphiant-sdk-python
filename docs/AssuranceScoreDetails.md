# AssuranceScoreDetails


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**score_bucket_list** | [**List[AssuranceScoreBucketCount]**](AssuranceScoreBucketCount.md) |  | [optional] 

## Example

```python
from graphiant_sdk.models.assurance_score_details import AssuranceScoreDetails

# TODO update the JSON string below
json = "{}"
# create an instance of AssuranceScoreDetails from a JSON string
assurance_score_details_instance = AssuranceScoreDetails.from_json(json)
# print the JSON string representation of the object
print(AssuranceScoreDetails.to_json())

# convert the object into a dict
assurance_score_details_dict = assurance_score_details_instance.to_dict()
# create an instance of AssuranceScoreDetails from a dict
assurance_score_details_from_dict = AssuranceScoreDetails.from_dict(assurance_score_details_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


