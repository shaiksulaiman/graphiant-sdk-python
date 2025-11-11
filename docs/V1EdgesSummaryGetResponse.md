# V1EdgesSummaryGetResponse


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**edges_summary** | [**List[SearchEdgeSummary]**](SearchEdgeSummary.md) |  | [optional] 
**is_new_count** | **int** |  | [optional] 

## Example

```python
from graphiant_sdk.models.v1_edges_summary_get_response import V1EdgesSummaryGetResponse

# TODO update the JSON string below
json = "{}"
# create an instance of V1EdgesSummaryGetResponse from a JSON string
v1_edges_summary_get_response_instance = V1EdgesSummaryGetResponse.from_json(json)
# print the JSON string representation of the object
print(V1EdgesSummaryGetResponse.to_json())

# convert the object into a dict
v1_edges_summary_get_response_dict = v1_edges_summary_get_response_instance.to_dict()
# create an instance of V1EdgesSummaryGetResponse from a dict
v1_edges_summary_get_response_from_dict = V1EdgesSummaryGetResponse.from_dict(v1_edges_summary_get_response_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


