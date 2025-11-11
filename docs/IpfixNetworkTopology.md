# IpfixNetworkTopology


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**circuit_status** | **Dict[str, int]** |  | [optional] 
**delta** | [**IpfixNetworkTopologyDelta**](IpfixNetworkTopologyDelta.md) |  | [optional] 
**edges** | [**List[ManaV2ConnectivityGraphEdge]**](ManaV2ConnectivityGraphEdge.md) |  | [optional] 
**flows** | **int** | Application flow count | [optional] 
**nodes** | [**List[ManaV2ConnectivityGraphNode]**](ManaV2ConnectivityGraphNode.md) |  | [optional] 
**time_window** | [**StatsmonTimeWindow**](StatsmonTimeWindow.md) |  | [optional] 

## Example

```python
from graphiant_sdk.models.ipfix_network_topology import IpfixNetworkTopology

# TODO update the JSON string below
json = "{}"
# create an instance of IpfixNetworkTopology from a JSON string
ipfix_network_topology_instance = IpfixNetworkTopology.from_json(json)
# print the JSON string representation of the object
print(IpfixNetworkTopology.to_json())

# convert the object into a dict
ipfix_network_topology_dict = ipfix_network_topology_instance.to_dict()
# create an instance of IpfixNetworkTopology from a dict
ipfix_network_topology_from_dict = IpfixNetworkTopology.from_dict(ipfix_network_topology_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


