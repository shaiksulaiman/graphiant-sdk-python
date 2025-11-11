# ManaV2StaticRouteNexthop


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**circuit** | **str** |  | [optional] 
**id** | **int** |  | [optional] 
**metric** | **int** |  | [optional] 
**next_hop_address** | **str** |  | [optional] 
**nexthop** | **str** |  | [optional] 
**outgoing_interface** | **str** |  | [optional] 
**third_party_ipsec_tunnel** | **str** |  | [optional] 

## Example

```python
from graphiant_sdk.models.mana_v2_static_route_nexthop import ManaV2StaticRouteNexthop

# TODO update the JSON string below
json = "{}"
# create an instance of ManaV2StaticRouteNexthop from a JSON string
mana_v2_static_route_nexthop_instance = ManaV2StaticRouteNexthop.from_json(json)
# print the JSON string representation of the object
print(ManaV2StaticRouteNexthop.to_json())

# convert the object into a dict
mana_v2_static_route_nexthop_dict = mana_v2_static_route_nexthop_instance.to_dict()
# create an instance of ManaV2StaticRouteNexthop from a dict
mana_v2_static_route_nexthop_from_dict = ManaV2StaticRouteNexthop.from_dict(mana_v2_static_route_nexthop_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


