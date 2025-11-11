# V1DeviceRoutingBgpNbrsPerAfiPrefixGetResponse


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**prefixes** | [**List[Routingprefix]**](Routingprefix.md) |  | [optional] 

## Example

```python
from graphiant_sdk.models.v1_device_routing_bgp_nbrs_per_afi_prefix_get_response import V1DeviceRoutingBgpNbrsPerAfiPrefixGetResponse

# TODO update the JSON string below
json = "{}"
# create an instance of V1DeviceRoutingBgpNbrsPerAfiPrefixGetResponse from a JSON string
v1_device_routing_bgp_nbrs_per_afi_prefix_get_response_instance = V1DeviceRoutingBgpNbrsPerAfiPrefixGetResponse.from_json(json)
# print the JSON string representation of the object
print(V1DeviceRoutingBgpNbrsPerAfiPrefixGetResponse.to_json())

# convert the object into a dict
v1_device_routing_bgp_nbrs_per_afi_prefix_get_response_dict = v1_device_routing_bgp_nbrs_per_afi_prefix_get_response_instance.to_dict()
# create an instance of V1DeviceRoutingBgpNbrsPerAfiPrefixGetResponse from a dict
v1_device_routing_bgp_nbrs_per_afi_prefix_get_response_from_dict = V1DeviceRoutingBgpNbrsPerAfiPrefixGetResponse.from_dict(v1_device_routing_bgp_nbrs_per_afi_prefix_get_response_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


