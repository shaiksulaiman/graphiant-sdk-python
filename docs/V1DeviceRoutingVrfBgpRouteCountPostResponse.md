# V1DeviceRoutingVrfBgpRouteCountPostResponse


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**counts** | [**List[V1DeviceRoutingVrfBgpRouteCountPostResponseRouteCount]**](V1DeviceRoutingVrfBgpRouteCountPostResponseRouteCount.md) |  | [optional] 

## Example

```python
from graphiant_sdk.models.v1_device_routing_vrf_bgp_route_count_post_response import V1DeviceRoutingVrfBgpRouteCountPostResponse

# TODO update the JSON string below
json = "{}"
# create an instance of V1DeviceRoutingVrfBgpRouteCountPostResponse from a JSON string
v1_device_routing_vrf_bgp_route_count_post_response_instance = V1DeviceRoutingVrfBgpRouteCountPostResponse.from_json(json)
# print the JSON string representation of the object
print(V1DeviceRoutingVrfBgpRouteCountPostResponse.to_json())

# convert the object into a dict
v1_device_routing_vrf_bgp_route_count_post_response_dict = v1_device_routing_vrf_bgp_route_count_post_response_instance.to_dict()
# create an instance of V1DeviceRoutingVrfBgpRouteCountPostResponse from a dict
v1_device_routing_vrf_bgp_route_count_post_response_from_dict = V1DeviceRoutingVrfBgpRouteCountPostResponse.from_dict(v1_device_routing_vrf_bgp_route_count_post_response_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


