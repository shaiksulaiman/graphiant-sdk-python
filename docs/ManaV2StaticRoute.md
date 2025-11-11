# ManaV2StaticRoute


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**administrative_distance** | **int** |  | [optional] 
**description** | **str** |  | [optional] 
**id** | **int** |  | [optional] 
**next_hop** | [**ManaV2StaticRouteNexthop**](ManaV2StaticRouteNexthop.md) |  | [optional] 
**next_hops** | [**List[ManaV2StaticRouteNexthop]**](ManaV2StaticRouteNexthop.md) |  | [optional] 
**prefix** | **str** |  | [optional] 

## Example

```python
from graphiant_sdk.models.mana_v2_static_route import ManaV2StaticRoute

# TODO update the JSON string below
json = "{}"
# create an instance of ManaV2StaticRoute from a JSON string
mana_v2_static_route_instance = ManaV2StaticRoute.from_json(json)
# print the JSON string representation of the object
print(ManaV2StaticRoute.to_json())

# convert the object into a dict
mana_v2_static_route_dict = mana_v2_static_route_instance.to_dict()
# create an instance of ManaV2StaticRoute from a dict
mana_v2_static_route_from_dict = ManaV2StaticRoute.from_dict(mana_v2_static_route_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


