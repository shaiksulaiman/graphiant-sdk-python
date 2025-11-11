# V1DevicesRoutingVrfProtocolRouteCountGetResponseProtocolCount


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**protocol** | **str** | Configured protocol (required) | [optional] 
**route_count** | [**RoutingAfiRouteCount**](RoutingAfiRouteCount.md) |  | [optional] 

## Example

```python
from graphiant_sdk.models.v1_devices_routing_vrf_protocol_route_count_get_response_protocol_count import V1DevicesRoutingVrfProtocolRouteCountGetResponseProtocolCount

# TODO update the JSON string below
json = "{}"
# create an instance of V1DevicesRoutingVrfProtocolRouteCountGetResponseProtocolCount from a JSON string
v1_devices_routing_vrf_protocol_route_count_get_response_protocol_count_instance = V1DevicesRoutingVrfProtocolRouteCountGetResponseProtocolCount.from_json(json)
# print the JSON string representation of the object
print(V1DevicesRoutingVrfProtocolRouteCountGetResponseProtocolCount.to_json())

# convert the object into a dict
v1_devices_routing_vrf_protocol_route_count_get_response_protocol_count_dict = v1_devices_routing_vrf_protocol_route_count_get_response_protocol_count_instance.to_dict()
# create an instance of V1DevicesRoutingVrfProtocolRouteCountGetResponseProtocolCount from a dict
v1_devices_routing_vrf_protocol_route_count_get_response_protocol_count_from_dict = V1DevicesRoutingVrfProtocolRouteCountGetResponseProtocolCount.from_dict(v1_devices_routing_vrf_protocol_route_count_get_response_protocol_count_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


