# V2AssuranceTopologyRegionSummaryPostResponseSiteEntry


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**edge_count** | **int** |  | [optional] 
**lan_segments** | **List[str]** |  | [optional] 
**pop_names** | **List[str]** |  | [optional] 
**region_name** | **str** |  | [optional] 
**site_id** | **int** |  | [optional] 
**site_name** | **str** |  | [optional] 
**tags** | **List[str]** |  | [optional] 

## Example

```python
from graphiant_sdk.models.v2_assurance_topology_region_summary_post_response_site_entry import V2AssuranceTopologyRegionSummaryPostResponseSiteEntry

# TODO update the JSON string below
json = "{}"
# create an instance of V2AssuranceTopologyRegionSummaryPostResponseSiteEntry from a JSON string
v2_assurance_topology_region_summary_post_response_site_entry_instance = V2AssuranceTopologyRegionSummaryPostResponseSiteEntry.from_json(json)
# print the JSON string representation of the object
print(V2AssuranceTopologyRegionSummaryPostResponseSiteEntry.to_json())

# convert the object into a dict
v2_assurance_topology_region_summary_post_response_site_entry_dict = v2_assurance_topology_region_summary_post_response_site_entry_instance.to_dict()
# create an instance of V2AssuranceTopologyRegionSummaryPostResponseSiteEntry from a dict
v2_assurance_topology_region_summary_post_response_site_entry_from_dict = V2AssuranceTopologyRegionSummaryPostResponseSiteEntry.from_dict(v2_assurance_topology_region_summary_post_response_site_entry_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


