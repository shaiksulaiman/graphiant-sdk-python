# AssuranceTopologyNode


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**active** | **bool** |  | [optional] 
**location** | [**AssuranceGeolocation**](AssuranceGeolocation.md) |  | [optional] 
**name** | **str** |  | [optional] 
**node_id** | **str** |  | [optional] 
**node_type** | **str** |  | [optional] 

## Example

```python
from graphiant_sdk.models.assurance_topology_node import AssuranceTopologyNode

# TODO update the JSON string below
json = "{}"
# create an instance of AssuranceTopologyNode from a JSON string
assurance_topology_node_instance = AssuranceTopologyNode.from_json(json)
# print the JSON string representation of the object
print(AssuranceTopologyNode.to_json())

# convert the object into a dict
assurance_topology_node_dict = assurance_topology_node_instance.to_dict()
# create an instance of AssuranceTopologyNode from a dict
assurance_topology_node_from_dict = AssuranceTopologyNode.from_dict(assurance_topology_node_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


