# AssuranceBucketSummary


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**assurance_bucket** | **str** |  | [optional] 
**bucket_color** | **str** |  | [optional] 
**bucket_name_to_display** | **str** |  | [optional] 
**bucket_stats** | [**AssuranceBucketStats**](AssuranceBucketStats.md) |  | [optional] 
**child_bucket_list** | **List[str]** |  | [optional] 
**child_bucket_stats_list** | [**List[AssuranceBucketStatsWithId]**](AssuranceBucketStatsWithId.md) |  | [optional] 
**is_root** | **bool** |  | [optional] 
**is_terminal** | **bool** |  | [optional] 
**parent_bucket_list** | **List[str]** |  | [optional] 

## Example

```python
from graphiant_sdk.models.assurance_bucket_summary import AssuranceBucketSummary

# TODO update the JSON string below
json = "{}"
# create an instance of AssuranceBucketSummary from a JSON string
assurance_bucket_summary_instance = AssuranceBucketSummary.from_json(json)
# print the JSON string representation of the object
print(AssuranceBucketSummary.to_json())

# convert the object into a dict
assurance_bucket_summary_dict = assurance_bucket_summary_instance.to_dict()
# create an instance of AssuranceBucketSummary from a dict
assurance_bucket_summary_from_dict = AssuranceBucketSummary.from_dict(assurance_bucket_summary_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


