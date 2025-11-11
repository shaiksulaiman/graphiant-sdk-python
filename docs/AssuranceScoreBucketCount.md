# AssuranceScoreBucketCount


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**curr_score** | **int** |  | [optional] 
**max_score** | **int** |  | [optional] 
**score_bucket_id** | **str** |  | [optional] 

## Example

```python
from graphiant_sdk.models.assurance_score_bucket_count import AssuranceScoreBucketCount

# TODO update the JSON string below
json = "{}"
# create an instance of AssuranceScoreBucketCount from a JSON string
assurance_score_bucket_count_instance = AssuranceScoreBucketCount.from_json(json)
# print the JSON string representation of the object
print(AssuranceScoreBucketCount.to_json())

# convert the object into a dict
assurance_score_bucket_count_dict = assurance_score_bucket_count_instance.to_dict()
# create an instance of AssuranceScoreBucketCount from a dict
assurance_score_bucket_count_from_dict = AssuranceScoreBucketCount.from_dict(assurance_score_bucket_count_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


