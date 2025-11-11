# V1GlobalSummaryPostResponse


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**summaries** | [**List[ManaV2GlobalObjectSummary]**](ManaV2GlobalObjectSummary.md) |  | [optional] 

## Example

```python
from graphiant_sdk.models.v1_global_summary_post_response import V1GlobalSummaryPostResponse

# TODO update the JSON string below
json = "{}"
# create an instance of V1GlobalSummaryPostResponse from a JSON string
v1_global_summary_post_response_instance = V1GlobalSummaryPostResponse.from_json(json)
# print the JSON string representation of the object
print(V1GlobalSummaryPostResponse.to_json())

# convert the object into a dict
v1_global_summary_post_response_dict = v1_global_summary_post_response_instance.to_dict()
# create an instance of V1GlobalSummaryPostResponse from a dict
v1_global_summary_post_response_from_dict = V1GlobalSummaryPostResponse.from_dict(v1_global_summary_post_response_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


