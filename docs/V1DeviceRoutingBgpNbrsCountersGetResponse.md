# V1DeviceRoutingBgpNbrsCountersGetResponse


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**counters** | [**List[RoutingbgpCounter]**](RoutingbgpCounter.md) |  | [optional] 

## Example

```python
from graphiant_sdk.models.v1_device_routing_bgp_nbrs_counters_get_response import V1DeviceRoutingBgpNbrsCountersGetResponse

# TODO update the JSON string below
json = "{}"
# create an instance of V1DeviceRoutingBgpNbrsCountersGetResponse from a JSON string
v1_device_routing_bgp_nbrs_counters_get_response_instance = V1DeviceRoutingBgpNbrsCountersGetResponse.from_json(json)
# print the JSON string representation of the object
print(V1DeviceRoutingBgpNbrsCountersGetResponse.to_json())

# convert the object into a dict
v1_device_routing_bgp_nbrs_counters_get_response_dict = v1_device_routing_bgp_nbrs_counters_get_response_instance.to_dict()
# create an instance of V1DeviceRoutingBgpNbrsCountersGetResponse from a dict
v1_device_routing_bgp_nbrs_counters_get_response_from_dict = V1DeviceRoutingBgpNbrsCountersGetResponse.from_dict(v1_device_routing_bgp_nbrs_counters_get_response_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


