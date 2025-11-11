# IpfixNetworkTopologyDelta


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**edges_added** | [**List[ManaV2ConnectivityGraphEdge]**](ManaV2ConnectivityGraphEdge.md) |  | [optional] 
**edges_deleted** | [**List[ManaV2ConnectivityGraphEdge]**](ManaV2ConnectivityGraphEdge.md) |  | [optional] 
**nodes_added** | [**List[ManaV2ConnectivityGraphNode]**](ManaV2ConnectivityGraphNode.md) |  | [optional] 
**nodes_deleted** | [**List[ManaV2ConnectivityGraphNode]**](ManaV2ConnectivityGraphNode.md) |  | [optional] 

## Example

```python
from graphiant_sdk.models.ipfix_network_topology_delta import IpfixNetworkTopologyDelta

# TODO update the JSON string below
json = "{}"
# create an instance of IpfixNetworkTopologyDelta from a JSON string
ipfix_network_topology_delta_instance = IpfixNetworkTopologyDelta.from_json(json)
# print the JSON string representation of the object
print(IpfixNetworkTopologyDelta.to_json())

# convert the object into a dict
ipfix_network_topology_delta_dict = ipfix_network_topology_delta_instance.to_dict()
# create an instance of IpfixNetworkTopologyDelta from a dict
ipfix_network_topology_delta_from_dict = IpfixNetworkTopologyDelta.from_dict(ipfix_network_topology_delta_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


