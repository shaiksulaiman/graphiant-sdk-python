# V1DeviceRoutingBgpNbrStatsGetResponse


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**page_info** | [**CommonPageInfo**](CommonPageInfo.md) |  | [optional] 
**stats** | [**RoutingNbrStats**](RoutingNbrStats.md) |  | [optional] 
**token** | **str** | Reference to the resultset being queried,this should be sent by the service as part of a previous request and so can be opaque to the client. | [optional] 

## Example

```python
from graphiant_sdk.models.v1_device_routing_bgp_nbr_stats_get_response import V1DeviceRoutingBgpNbrStatsGetResponse

# TODO update the JSON string below
json = "{}"
# create an instance of V1DeviceRoutingBgpNbrStatsGetResponse from a JSON string
v1_device_routing_bgp_nbr_stats_get_response_instance = V1DeviceRoutingBgpNbrStatsGetResponse.from_json(json)
# print the JSON string representation of the object
print(V1DeviceRoutingBgpNbrStatsGetResponse.to_json())

# convert the object into a dict
v1_device_routing_bgp_nbr_stats_get_response_dict = v1_device_routing_bgp_nbr_stats_get_response_instance.to_dict()
# create an instance of V1DeviceRoutingBgpNbrStatsGetResponse from a dict
v1_device_routing_bgp_nbr_stats_get_response_from_dict = V1DeviceRoutingBgpNbrStatsGetResponse.from_dict(v1_device_routing_bgp_nbr_stats_get_response_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


