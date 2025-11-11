# AssuranceBucketStatsWithId


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**assurance_bucket** | **str** |  | [optional] 
**bucket_name_to_display** | **str** |  | [optional] 
**prev_unique_app_count** | **int** |  | [optional] 
**unique_app_count** | **int** |  | [optional] 

## Example

```python
from graphiant_sdk.models.assurance_bucket_stats_with_id import AssuranceBucketStatsWithId

# TODO update the JSON string below
json = "{}"
# create an instance of AssuranceBucketStatsWithId from a JSON string
assurance_bucket_stats_with_id_instance = AssuranceBucketStatsWithId.from_json(json)
# print the JSON string representation of the object
print(AssuranceBucketStatsWithId.to_json())

# convert the object into a dict
assurance_bucket_stats_with_id_dict = assurance_bucket_stats_with_id_instance.to_dict()
# create an instance of AssuranceBucketStatsWithId from a dict
assurance_bucket_stats_with_id_from_dict = AssuranceBucketStatsWithId.from_dict(assurance_bucket_stats_with_id_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


