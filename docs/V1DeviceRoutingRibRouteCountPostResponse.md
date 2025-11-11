# V1DeviceRoutingRibRouteCountPostResponse


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**counts** | [**List[V1DeviceRoutingRibRouteCountPostResponseRouteCount]**](V1DeviceRoutingRibRouteCountPostResponseRouteCount.md) |  | [optional] 

## Example

```python
from graphiant_sdk.models.v1_device_routing_rib_route_count_post_response import V1DeviceRoutingRibRouteCountPostResponse

# TODO update the JSON string below
json = "{}"
# create an instance of V1DeviceRoutingRibRouteCountPostResponse from a JSON string
v1_device_routing_rib_route_count_post_response_instance = V1DeviceRoutingRibRouteCountPostResponse.from_json(json)
# print the JSON string representation of the object
print(V1DeviceRoutingRibRouteCountPostResponse.to_json())

# convert the object into a dict
v1_device_routing_rib_route_count_post_response_dict = v1_device_routing_rib_route_count_post_response_instance.to_dict()
# create an instance of V1DeviceRoutingRibRouteCountPostResponse from a dict
v1_device_routing_rib_route_count_post_response_from_dict = V1DeviceRoutingRibRouteCountPostResponse.from_dict(v1_device_routing_rib_route_count_post_response_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


