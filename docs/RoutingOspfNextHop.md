# RoutingOspfNextHop


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**egress_interface** | **str** | Interface name (required) | [optional] 
**last_modified** | [**GoogleProtobufTimestamp**](GoogleProtobufTimestamp.md) |  | [optional] 
**metric** | **int** | value &gt; 0 (required) | [optional] 
**next_hop** | **str** | IPv4 or IPv6 Nexthop (required) | [optional] 
**tag** | **int** | admin assigned number (required) | [optional] 
**type** | **str** | route type (required) | [optional] 

## Example

```python
from graphiant_sdk.models.routing_ospf_next_hop import RoutingOspfNextHop

# TODO update the JSON string below
json = "{}"
# create an instance of RoutingOspfNextHop from a JSON string
routing_ospf_next_hop_instance = RoutingOspfNextHop.from_json(json)
# print the JSON string representation of the object
print(RoutingOspfNextHop.to_json())

# convert the object into a dict
routing_ospf_next_hop_dict = routing_ospf_next_hop_instance.to_dict()
# create an instance of RoutingOspfNextHop from a dict
routing_ospf_next_hop_from_dict = RoutingOspfNextHop.from_dict(routing_ospf_next_hop_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


