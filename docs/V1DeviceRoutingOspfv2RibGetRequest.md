# V1DeviceRoutingOspfv2RibGetRequest


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**filter** | [**RoutingPrefixFilter**](RoutingPrefixFilter.md) |  | [optional] 
**page_request** | [**CommonPageRequest**](CommonPageRequest.md) |  | [optional] 

## Example

```python
from graphiant_sdk.models.v1_device_routing_ospfv2_rib_get_request import V1DeviceRoutingOspfv2RibGetRequest

# TODO update the JSON string below
json = "{}"
# create an instance of V1DeviceRoutingOspfv2RibGetRequest from a JSON string
v1_device_routing_ospfv2_rib_get_request_instance = V1DeviceRoutingOspfv2RibGetRequest.from_json(json)
# print the JSON string representation of the object
print(V1DeviceRoutingOspfv2RibGetRequest.to_json())

# convert the object into a dict
v1_device_routing_ospfv2_rib_get_request_dict = v1_device_routing_ospfv2_rib_get_request_instance.to_dict()
# create an instance of V1DeviceRoutingOspfv2RibGetRequest from a dict
v1_device_routing_ospfv2_rib_get_request_from_dict = V1DeviceRoutingOspfv2RibGetRequest.from_dict(v1_device_routing_ospfv2_rib_get_request_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


