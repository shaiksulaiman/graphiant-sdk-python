# V1FlowsTopologyPostResponse


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**network_topology** | [**List[IpfixNetworkTopology]**](IpfixNetworkTopology.md) |  | [optional] 

## Example

```python
from graphiant_sdk.models.v1_flows_topology_post_response import V1FlowsTopologyPostResponse

# TODO update the JSON string below
json = "{}"
# create an instance of V1FlowsTopologyPostResponse from a JSON string
v1_flows_topology_post_response_instance = V1FlowsTopologyPostResponse.from_json(json)
# print the JSON string representation of the object
print(V1FlowsTopologyPostResponse.to_json())

# convert the object into a dict
v1_flows_topology_post_response_dict = v1_flows_topology_post_response_instance.to_dict()
# create an instance of V1FlowsTopologyPostResponse from a dict
v1_flows_topology_post_response_from_dict = V1FlowsTopologyPostResponse.from_dict(v1_flows_topology_post_response_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


