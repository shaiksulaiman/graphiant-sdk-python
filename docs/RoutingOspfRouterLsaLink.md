# RoutingOspfRouterLsaLink


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**link_data** | **str** |  | [optional] 
**link_id** | **str** |  | [optional] 
**link_type** | **str** |  | [optional] 
**metric** | **int** |  | [optional] 
**tos_metric** | [**RoutingOspflsaTosMetric**](RoutingOspflsaTosMetric.md) |  | [optional] 

## Example

```python
from graphiant_sdk.models.routing_ospf_router_lsa_link import RoutingOspfRouterLsaLink

# TODO update the JSON string below
json = "{}"
# create an instance of RoutingOspfRouterLsaLink from a JSON string
routing_ospf_router_lsa_link_instance = RoutingOspfRouterLsaLink.from_json(json)
# print the JSON string representation of the object
print(RoutingOspfRouterLsaLink.to_json())

# convert the object into a dict
routing_ospf_router_lsa_link_dict = routing_ospf_router_lsa_link_instance.to_dict()
# create an instance of RoutingOspfRouterLsaLink from a dict
routing_ospf_router_lsa_link_from_dict = RoutingOspfRouterLsaLink.from_dict(routing_ospf_router_lsa_link_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


