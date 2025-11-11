# IamCounts


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**active_down_count** | **int** |  | [optional] 
**active_up_count** | **int** |  | [optional] 
**deactivated_down_count** | **int** |  | [optional] 
**down_sites_count** | **int** |  | [optional] 
**empty_sites_count** | **int** |  | [optional] 
**impaired_sites_count** | **int** |  | [optional] 
**staging_down_count** | **int** |  | [optional] 
**staging_up_count** | **int** |  | [optional] 
**total_customers** | **int** |  | [optional] 
**total_edges** | **int** |  | [optional] 
**total_msps** | **int** |  | [optional] 
**total_sites** | **int** |  | [optional] 
**up_sites_count** | **int** |  | [optional] 

## Example

```python
from graphiant_sdk.models.iam_counts import IamCounts

# TODO update the JSON string below
json = "{}"
# create an instance of IamCounts from a JSON string
iam_counts_instance = IamCounts.from_json(json)
# print the JSON string representation of the object
print(IamCounts.to_json())

# convert the object into a dict
iam_counts_dict = iam_counts_instance.to_dict()
# create an instance of IamCounts from a dict
iam_counts_from_dict = IamCounts.from_dict(iam_counts_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


