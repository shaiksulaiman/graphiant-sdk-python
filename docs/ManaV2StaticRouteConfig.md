# ManaV2StaticRouteConfig


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**admin_distance** | **int** |  | [optional] 
**administrative_distance** | [**ManaV2NullableAdministrativeDistance**](ManaV2NullableAdministrativeDistance.md) |  | [optional] 
**description** | **str** |  | [optional] 
**destination_prefix** | **str** |  | [optional] 
**ip_version** | **int** |  | [optional] 
**next_hop** | [**ManaV2StaticRouteNexthopConfig**](ManaV2StaticRouteNexthopConfig.md) |  | [optional] 
**next_hops** | [**List[ManaV2StaticRouteNexthopConfig]**](ManaV2StaticRouteNexthopConfig.md) |  | [optional] 

## Example

```python
from graphiant_sdk.models.mana_v2_static_route_config import ManaV2StaticRouteConfig

# TODO update the JSON string below
json = "{}"
# create an instance of ManaV2StaticRouteConfig from a JSON string
mana_v2_static_route_config_instance = ManaV2StaticRouteConfig.from_json(json)
# print the JSON string representation of the object
print(ManaV2StaticRouteConfig.to_json())

# convert the object into a dict
mana_v2_static_route_config_dict = mana_v2_static_route_config_instance.to_dict()
# create an instance of ManaV2StaticRouteConfig from a dict
mana_v2_static_route_config_from_dict = ManaV2StaticRouteConfig.from_dict(mana_v2_static_route_config_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


