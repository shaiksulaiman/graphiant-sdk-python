# RoutingOspfRoute


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**ip_prefix** | **str** | IPv4 or IPv6 Prefix (required) | [optional] 
**path** | [**List[RoutingOspfNextHop]**](RoutingOspfNextHop.md) |  | [optional] 

## Example

```python
from graphiant_sdk.models.routing_ospf_route import RoutingOspfRoute

# TODO update the JSON string below
json = "{}"
# create an instance of RoutingOspfRoute from a JSON string
routing_ospf_route_instance = RoutingOspfRoute.from_json(json)
# print the JSON string representation of the object
print(RoutingOspfRoute.to_json())

# convert the object into a dict
routing_ospf_route_dict = routing_ospf_route_instance.to_dict()
# create an instance of RoutingOspfRoute from a dict
routing_ospf_route_from_dict = RoutingOspfRoute.from_dict(routing_ospf_route_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


