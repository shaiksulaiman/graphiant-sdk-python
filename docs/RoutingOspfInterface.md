# RoutingOspfInterface


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**bdr_ip_addr** | **str** | Router IP Address (required) | [optional] 
**bdr_router_id** | **str** | BDR Router ID (required) | [optional] 
**dr_ip_addr** | **str** | Router IP Address (required) | [optional] 
**dr_router_id** | **str** | Router ID (required) | [optional] 
**hello_interval** | **str** |  | [optional] 
**hello_timer** | **str** | Timer in seconds (required) | [optional] 
**name** | **str** | Interface name (required) | [optional] 
**neighbors** | **List[str]** |  | [optional] 
**state** | **str** | interface state (required) | [optional] 
**wait_timer** | **str** | Timer in seconds (required) | [optional] 

## Example

```python
from graphiant_sdk.models.routing_ospf_interface import RoutingOspfInterface

# TODO update the JSON string below
json = "{}"
# create an instance of RoutingOspfInterface from a JSON string
routing_ospf_interface_instance = RoutingOspfInterface.from_json(json)
# print the JSON string representation of the object
print(RoutingOspfInterface.to_json())

# convert the object into a dict
routing_ospf_interface_dict = routing_ospf_interface_instance.to_dict()
# create an instance of RoutingOspfInterface from a dict
routing_ospf_interface_from_dict = RoutingOspfInterface.from_dict(routing_ospf_interface_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


