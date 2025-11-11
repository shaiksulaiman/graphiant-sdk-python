# RoutingOspfRouterLsa


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**links** | [**List[RoutingOspfRouterLsaLink]**](RoutingOspfRouterLsaLink.md) |  | [optional] 

## Example

```python
from graphiant_sdk.models.routing_ospf_router_lsa import RoutingOspfRouterLsa

# TODO update the JSON string below
json = "{}"
# create an instance of RoutingOspfRouterLsa from a JSON string
routing_ospf_router_lsa_instance = RoutingOspfRouterLsa.from_json(json)
# print the JSON string representation of the object
print(RoutingOspfRouterLsa.to_json())

# convert the object into a dict
routing_ospf_router_lsa_dict = routing_ospf_router_lsa_instance.to_dict()
# create an instance of RoutingOspfRouterLsa from a dict
routing_ospf_router_lsa_from_dict = RoutingOspfRouterLsa.from_dict(routing_ospf_router_lsa_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


