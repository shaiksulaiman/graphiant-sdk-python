# AssuranceBucketStats


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**prev_unique_app_count** | **int** |  | [optional] 
**prev_unique_threat_count** | **int** |  | [optional] 
**unique_app_count** | **int** |  | [optional] 
**unique_threat_count** | **int** |  | [optional] 

## Example

```python
from graphiant_sdk.models.assurance_bucket_stats import AssuranceBucketStats

# TODO update the JSON string below
json = "{}"
# create an instance of AssuranceBucketStats from a JSON string
assurance_bucket_stats_instance = AssuranceBucketStats.from_json(json)
# print the JSON string representation of the object
print(AssuranceBucketStats.to_json())

# convert the object into a dict
assurance_bucket_stats_dict = assurance_bucket_stats_instance.to_dict()
# create an instance of AssuranceBucketStats from a dict
assurance_bucket_stats_from_dict = AssuranceBucketStats.from_dict(assurance_bucket_stats_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


