# ManaV2ConnectivityGraphEdge


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**a** | **int** |  | [optional] 
**b** | **int** |  | [optional] 
**connections** | [**ManaV2GraphiantConnections**](ManaV2GraphiantConnections.md) |  | [optional] 
**quality** | **str** |  | [optional] 

## Example

```python
from graphiant_sdk.models.mana_v2_connectivity_graph_edge import ManaV2ConnectivityGraphEdge

# TODO update the JSON string below
json = "{}"
# create an instance of ManaV2ConnectivityGraphEdge from a JSON string
mana_v2_connectivity_graph_edge_instance = ManaV2ConnectivityGraphEdge.from_json(json)
# print the JSON string representation of the object
print(ManaV2ConnectivityGraphEdge.to_json())

# convert the object into a dict
mana_v2_connectivity_graph_edge_dict = mana_v2_connectivity_graph_edge_instance.to_dict()
# create an instance of ManaV2ConnectivityGraphEdge from a dict
mana_v2_connectivity_graph_edge_from_dict = ManaV2ConnectivityGraphEdge.from_dict(mana_v2_connectivity_graph_edge_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


