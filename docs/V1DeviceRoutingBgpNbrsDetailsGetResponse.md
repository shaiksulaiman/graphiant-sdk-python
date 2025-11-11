# V1DeviceRoutingBgpNbrsDetailsGetResponse


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**ebgp_multi_hop_ttl** | **int** |  | [optional] 
**hold_timer** | **int** |  | [optional] 
**keep_alive_timer** | **int** |  | [optional] 

## Example

```python
from graphiant_sdk.models.v1_device_routing_bgp_nbrs_details_get_response import V1DeviceRoutingBgpNbrsDetailsGetResponse

# TODO update the JSON string below
json = "{}"
# create an instance of V1DeviceRoutingBgpNbrsDetailsGetResponse from a JSON string
v1_device_routing_bgp_nbrs_details_get_response_instance = V1DeviceRoutingBgpNbrsDetailsGetResponse.from_json(json)
# print the JSON string representation of the object
print(V1DeviceRoutingBgpNbrsDetailsGetResponse.to_json())

# convert the object into a dict
v1_device_routing_bgp_nbrs_details_get_response_dict = v1_device_routing_bgp_nbrs_details_get_response_instance.to_dict()
# create an instance of V1DeviceRoutingBgpNbrsDetailsGetResponse from a dict
v1_device_routing_bgp_nbrs_details_get_response_from_dict = V1DeviceRoutingBgpNbrsDetailsGetResponse.from_dict(v1_device_routing_bgp_nbrs_details_get_response_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


