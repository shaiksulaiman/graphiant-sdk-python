# AssuranceTopologyFilter


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**client_site_ids** | **List[int]** |  | [optional] 
**region_ids** | **List[int]** |  | [optional] 
**server_site_ids** | **List[int]** |  | [optional] 

## Example

```python
from graphiant_sdk.models.assurance_topology_filter import AssuranceTopologyFilter

# TODO update the JSON string below
json = "{}"
# create an instance of AssuranceTopologyFilter from a JSON string
assurance_topology_filter_instance = AssuranceTopologyFilter.from_json(json)
# print the JSON string representation of the object
print(AssuranceTopologyFilter.to_json())

# convert the object into a dict
assurance_topology_filter_dict = assurance_topology_filter_instance.to_dict()
# create an instance of AssuranceTopologyFilter from a dict
assurance_topology_filter_from_dict = AssuranceTopologyFilter.from_dict(assurance_topology_filter_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


