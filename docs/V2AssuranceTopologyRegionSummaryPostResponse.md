# V2AssuranceTopologyRegionSummaryPostResponse


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**sites** | [**List[V2AssuranceTopologyRegionSummaryPostResponseSiteEntry]**](V2AssuranceTopologyRegionSummaryPostResponseSiteEntry.md) |  | [optional] 

## Example

```python
from graphiant_sdk.models.v2_assurance_topology_region_summary_post_response import V2AssuranceTopologyRegionSummaryPostResponse

# TODO update the JSON string below
json = "{}"
# create an instance of V2AssuranceTopologyRegionSummaryPostResponse from a JSON string
v2_assurance_topology_region_summary_post_response_instance = V2AssuranceTopologyRegionSummaryPostResponse.from_json(json)
# print the JSON string representation of the object
print(V2AssuranceTopologyRegionSummaryPostResponse.to_json())

# convert the object into a dict
v2_assurance_topology_region_summary_post_response_dict = v2_assurance_topology_region_summary_post_response_instance.to_dict()
# create an instance of V2AssuranceTopologyRegionSummaryPostResponse from a dict
v2_assurance_topology_region_summary_post_response_from_dict = V2AssuranceTopologyRegionSummaryPostResponse.from_dict(v2_assurance_topology_region_summary_post_response_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


