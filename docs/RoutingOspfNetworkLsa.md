# RoutingOspfNetworkLsa


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**attached_routers** | **List[str]** |  | [optional] 
**network_mask** | **int** |  | [optional] 

## Example

```python
from graphiant_sdk.models.routing_ospf_network_lsa import RoutingOspfNetworkLsa

# TODO update the JSON string below
json = "{}"
# create an instance of RoutingOspfNetworkLsa from a JSON string
routing_ospf_network_lsa_instance = RoutingOspfNetworkLsa.from_json(json)
# print the JSON string representation of the object
print(RoutingOspfNetworkLsa.to_json())

# convert the object into a dict
routing_ospf_network_lsa_dict = routing_ospf_network_lsa_instance.to_dict()
# create an instance of RoutingOspfNetworkLsa from a dict
routing_ospf_network_lsa_from_dict = RoutingOspfNetworkLsa.from_dict(routing_ospf_network_lsa_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


