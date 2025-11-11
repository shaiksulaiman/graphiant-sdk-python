# AssuranceTopologyEdgeLinkPerformance


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**jitter** | **float** |  | [optional] 
**latency** | **float** |  | [optional] 
**loss** | **float** |  | [optional] 

## Example

```python
from graphiant_sdk.models.assurance_topology_edge_link_performance import AssuranceTopologyEdgeLinkPerformance

# TODO update the JSON string below
json = "{}"
# create an instance of AssuranceTopologyEdgeLinkPerformance from a JSON string
assurance_topology_edge_link_performance_instance = AssuranceTopologyEdgeLinkPerformance.from_json(json)
# print the JSON string representation of the object
print(AssuranceTopologyEdgeLinkPerformance.to_json())

# convert the object into a dict
assurance_topology_edge_link_performance_dict = assurance_topology_edge_link_performance_instance.to_dict()
# create an instance of AssuranceTopologyEdgeLinkPerformance from a dict
assurance_topology_edge_link_performance_from_dict = AssuranceTopologyEdgeLinkPerformance.from_dict(assurance_topology_edge_link_performance_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


