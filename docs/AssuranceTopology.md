# AssuranceTopology


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**edges** | [**List[AssuranceTopologyEdge]**](AssuranceTopologyEdge.md) |  | [optional] 
**nodes** | [**List[AssuranceTopologyNode]**](AssuranceTopologyNode.md) |  | [optional] 
**paths** | [**List[AssuranceTopologyPath]**](AssuranceTopologyPath.md) |  | [optional] 

## Example

```python
from graphiant_sdk.models.assurance_topology import AssuranceTopology

# TODO update the JSON string below
json = "{}"
# create an instance of AssuranceTopology from a JSON string
assurance_topology_instance = AssuranceTopology.from_json(json)
# print the JSON string representation of the object
print(AssuranceTopology.to_json())

# convert the object into a dict
assurance_topology_dict = assurance_topology_instance.to_dict()
# create an instance of AssuranceTopology from a dict
assurance_topology_from_dict = AssuranceTopology.from_dict(assurance_topology_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


