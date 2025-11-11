# AssuranceTopologyEdge


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**destination_node_id** | **str** |  | [optional] 
**performance** | [**List[AssuranceTopologyEdgeLinkPerformance]**](AssuranceTopologyEdgeLinkPerformance.md) |  | [optional] 
**source_node_id** | **str** |  | [optional] 

## Example

```python
from graphiant_sdk.models.assurance_topology_edge import AssuranceTopologyEdge

# TODO update the JSON string below
json = "{}"
# create an instance of AssuranceTopologyEdge from a JSON string
assurance_topology_edge_instance = AssuranceTopologyEdge.from_json(json)
# print the JSON string representation of the object
print(AssuranceTopologyEdge.to_json())

# convert the object into a dict
assurance_topology_edge_dict = assurance_topology_edge_instance.to_dict()
# create an instance of AssuranceTopologyEdge from a dict
assurance_topology_edge_from_dict = AssuranceTopologyEdge.from_dict(assurance_topology_edge_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


