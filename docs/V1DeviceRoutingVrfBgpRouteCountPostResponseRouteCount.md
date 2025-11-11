# V1DeviceRoutingVrfBgpRouteCountPostResponseRouteCount


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**route_count** | **int** | total route count in a vrf (required) | [optional] 
**vrf_name** | **str** | Valid configured VRF name (required) | [optional] 

## Example

```python
from graphiant_sdk.models.v1_device_routing_vrf_bgp_route_count_post_response_route_count import V1DeviceRoutingVrfBgpRouteCountPostResponseRouteCount

# TODO update the JSON string below
json = "{}"
# create an instance of V1DeviceRoutingVrfBgpRouteCountPostResponseRouteCount from a JSON string
v1_device_routing_vrf_bgp_route_count_post_response_route_count_instance = V1DeviceRoutingVrfBgpRouteCountPostResponseRouteCount.from_json(json)
# print the JSON string representation of the object
print(V1DeviceRoutingVrfBgpRouteCountPostResponseRouteCount.to_json())

# convert the object into a dict
v1_device_routing_vrf_bgp_route_count_post_response_route_count_dict = v1_device_routing_vrf_bgp_route_count_post_response_route_count_instance.to_dict()
# create an instance of V1DeviceRoutingVrfBgpRouteCountPostResponseRouteCount from a dict
v1_device_routing_vrf_bgp_route_count_post_response_route_count_from_dict = V1DeviceRoutingVrfBgpRouteCountPostResponseRouteCount.from_dict(v1_device_routing_vrf_bgp_route_count_post_response_route_count_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


