# V2AssuranceTopologySiteSummariesPostResponseSummary


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**app_name** | **str** |  | [optional] 
**lan_segments** | **List[str]** |  | [optional] 
**session_count** | **int** |  | [optional] 
**site** | [**AssuranceSite**](AssuranceSite.md) |  | [optional] 

## Example

```python
from graphiant_sdk.models.v2_assurance_topology_site_summaries_post_response_summary import V2AssuranceTopologySiteSummariesPostResponseSummary

# TODO update the JSON string below
json = "{}"
# create an instance of V2AssuranceTopologySiteSummariesPostResponseSummary from a JSON string
v2_assurance_topology_site_summaries_post_response_summary_instance = V2AssuranceTopologySiteSummariesPostResponseSummary.from_json(json)
# print the JSON string representation of the object
print(V2AssuranceTopologySiteSummariesPostResponseSummary.to_json())

# convert the object into a dict
v2_assurance_topology_site_summaries_post_response_summary_dict = v2_assurance_topology_site_summaries_post_response_summary_instance.to_dict()
# create an instance of V2AssuranceTopologySiteSummariesPostResponseSummary from a dict
v2_assurance_topology_site_summaries_post_response_summary_from_dict = V2AssuranceTopologySiteSummariesPostResponseSummary.from_dict(v2_assurance_topology_site_summaries_post_response_summary_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


