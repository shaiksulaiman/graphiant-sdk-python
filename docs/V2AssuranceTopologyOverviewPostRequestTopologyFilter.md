# V2AssuranceTopologyOverviewPostRequestTopologyFilter


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**client_site_ids** | **List[int]** |  | [optional] 
**region_ids** | **List[int]** |  | [optional] 
**server_site_ids** | **List[int]** |  | [optional] 

## Example

```python
from graphiant_sdk.models.v2_assurance_topology_overview_post_request_topology_filter import V2AssuranceTopologyOverviewPostRequestTopologyFilter

# TODO update the JSON string below
json = "{}"
# create an instance of V2AssuranceTopologyOverviewPostRequestTopologyFilter from a JSON string
v2_assurance_topology_overview_post_request_topology_filter_instance = V2AssuranceTopologyOverviewPostRequestTopologyFilter.from_json(json)
# print the JSON string representation of the object
print(V2AssuranceTopologyOverviewPostRequestTopologyFilter.to_json())

# convert the object into a dict
v2_assurance_topology_overview_post_request_topology_filter_dict = v2_assurance_topology_overview_post_request_topology_filter_instance.to_dict()
# create an instance of V2AssuranceTopologyOverviewPostRequestTopologyFilter from a dict
v2_assurance_topology_overview_post_request_topology_filter_from_dict = V2AssuranceTopologyOverviewPostRequestTopologyFilter.from_dict(v2_assurance_topology_overview_post_request_topology_filter_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


