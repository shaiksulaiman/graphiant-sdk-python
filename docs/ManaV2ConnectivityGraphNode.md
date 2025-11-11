# ManaV2ConnectivityGraphNode


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**connections** | [**ManaV2GraphiantConnections**](ManaV2GraphiantConnections.md) |  | [optional] 
**id** | **int** |  | [optional] 
**name** | **str** |  | [optional] 
**override_region** | **str** |  | [optional] 
**region** | **str** |  | [optional] 
**type** | **str** |  | [optional] 

## Example

```python
from graphiant_sdk.models.mana_v2_connectivity_graph_node import ManaV2ConnectivityGraphNode

# TODO update the JSON string below
json = "{}"
# create an instance of ManaV2ConnectivityGraphNode from a JSON string
mana_v2_connectivity_graph_node_instance = ManaV2ConnectivityGraphNode.from_json(json)
# print the JSON string representation of the object
print(ManaV2ConnectivityGraphNode.to_json())

# convert the object into a dict
mana_v2_connectivity_graph_node_dict = mana_v2_connectivity_graph_node_instance.to_dict()
# create an instance of ManaV2ConnectivityGraphNode from a dict
mana_v2_connectivity_graph_node_from_dict = ManaV2ConnectivityGraphNode.from_dict(mana_v2_connectivity_graph_node_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


