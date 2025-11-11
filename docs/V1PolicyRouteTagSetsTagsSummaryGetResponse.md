# V1PolicyRouteTagSetsTagsSummaryGetResponse


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**tags** | [**List[ManaV2RouteTagSummary]**](ManaV2RouteTagSummary.md) |  | [optional] 

## Example

```python
from graphiant_sdk.models.v1_policy_route_tag_sets_tags_summary_get_response import V1PolicyRouteTagSetsTagsSummaryGetResponse

# TODO update the JSON string below
json = "{}"
# create an instance of V1PolicyRouteTagSetsTagsSummaryGetResponse from a JSON string
v1_policy_route_tag_sets_tags_summary_get_response_instance = V1PolicyRouteTagSetsTagsSummaryGetResponse.from_json(json)
# print the JSON string representation of the object
print(V1PolicyRouteTagSetsTagsSummaryGetResponse.to_json())

# convert the object into a dict
v1_policy_route_tag_sets_tags_summary_get_response_dict = v1_policy_route_tag_sets_tags_summary_get_response_instance.to_dict()
# create an instance of V1PolicyRouteTagSetsTagsSummaryGetResponse from a dict
v1_policy_route_tag_sets_tags_summary_get_response_from_dict = V1PolicyRouteTagSetsTagsSummaryGetResponse.from_dict(v1_policy_route_tag_sets_tags_summary_get_response_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


