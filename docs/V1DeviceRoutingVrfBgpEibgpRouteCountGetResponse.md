# V1DeviceRoutingVrfBgpEibgpRouteCountGetResponse


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**ebgp_route_count** | [**RoutingAfiRouteCount**](RoutingAfiRouteCount.md) |  | [optional] 
**graphiant_route_count** | [**RoutingAfiRouteCount**](RoutingAfiRouteCount.md) |  | [optional] 
**ibgp_route_count** | [**RoutingAfiRouteCount**](RoutingAfiRouteCount.md) |  | [optional] 
**local_sourced_route_count** | [**RoutingAfiRouteCount**](RoutingAfiRouteCount.md) |  | [optional] 
**total_route_count** | [**RoutingAfiRouteCount**](RoutingAfiRouteCount.md) |  | [optional] 

## Example

```python
from graphiant_sdk.models.v1_device_routing_vrf_bgp_eibgp_route_count_get_response import V1DeviceRoutingVrfBgpEibgpRouteCountGetResponse

# TODO update the JSON string below
json = "{}"
# create an instance of V1DeviceRoutingVrfBgpEibgpRouteCountGetResponse from a JSON string
v1_device_routing_vrf_bgp_eibgp_route_count_get_response_instance = V1DeviceRoutingVrfBgpEibgpRouteCountGetResponse.from_json(json)
# print the JSON string representation of the object
print(V1DeviceRoutingVrfBgpEibgpRouteCountGetResponse.to_json())

# convert the object into a dict
v1_device_routing_vrf_bgp_eibgp_route_count_get_response_dict = v1_device_routing_vrf_bgp_eibgp_route_count_get_response_instance.to_dict()
# create an instance of V1DeviceRoutingVrfBgpEibgpRouteCountGetResponse from a dict
v1_device_routing_vrf_bgp_eibgp_route_count_get_response_from_dict = V1DeviceRoutingVrfBgpEibgpRouteCountGetResponse.from_dict(v1_device_routing_vrf_bgp_eibgp_route_count_get_response_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


