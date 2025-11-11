# V1DeviceRoutingBgpNbrsCountersGetRequest


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**address** | **str** | BGP Nbr address (required) | 
**device_id** | **int** | Valid configured device ID &gt; 0 (required) | 
**vrf_name** | **str** | Valid configured VRF name (required) | 

## Example

```python
from graphiant_sdk.models.v1_device_routing_bgp_nbrs_counters_get_request import V1DeviceRoutingBgpNbrsCountersGetRequest

# TODO update the JSON string below
json = "{}"
# create an instance of V1DeviceRoutingBgpNbrsCountersGetRequest from a JSON string
v1_device_routing_bgp_nbrs_counters_get_request_instance = V1DeviceRoutingBgpNbrsCountersGetRequest.from_json(json)
# print the JSON string representation of the object
print(V1DeviceRoutingBgpNbrsCountersGetRequest.to_json())

# convert the object into a dict
v1_device_routing_bgp_nbrs_counters_get_request_dict = v1_device_routing_bgp_nbrs_counters_get_request_instance.to_dict()
# create an instance of V1DeviceRoutingBgpNbrsCountersGetRequest from a dict
v1_device_routing_bgp_nbrs_counters_get_request_from_dict = V1DeviceRoutingBgpNbrsCountersGetRequest.from_dict(v1_device_routing_bgp_nbrs_counters_get_request_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


