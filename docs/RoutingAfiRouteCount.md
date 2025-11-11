# RoutingAfiRouteCount


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**ipv4** | **int** | IPv4 route count | [optional] 
**ipv6** | **int** | IPv6 route count | [optional] 

## Example

```python
from graphiant_sdk.models.routing_afi_route_count import RoutingAfiRouteCount

# TODO update the JSON string below
json = "{}"
# create an instance of RoutingAfiRouteCount from a JSON string
routing_afi_route_count_instance = RoutingAfiRouteCount.from_json(json)
# print the JSON string representation of the object
print(RoutingAfiRouteCount.to_json())

# convert the object into a dict
routing_afi_route_count_dict = routing_afi_route_count_instance.to_dict()
# create an instance of RoutingAfiRouteCount from a dict
routing_afi_route_count_from_dict = RoutingAfiRouteCount.from_dict(routing_afi_route_count_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


