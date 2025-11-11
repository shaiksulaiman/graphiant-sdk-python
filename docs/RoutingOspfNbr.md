# RoutingOspfNbr


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**address** | **str** | v4 or v6 Address (required) | [optional] 
**cost** | **int** | cost (required) | [optional] 
**dead_timer** | **int** | Dead Timer (required) | [optional] 
**last_state_change** | [**GoogleProtobufTimestamp**](GoogleProtobufTimestamp.md) |  | [optional] 
**router_id** | **str** | Router ID (required) | [optional] 
**state** | **str** | interface state (required) | [optional] 

## Example

```python
from graphiant_sdk.models.routing_ospf_nbr import RoutingOspfNbr

# TODO update the JSON string below
json = "{}"
# create an instance of RoutingOspfNbr from a JSON string
routing_ospf_nbr_instance = RoutingOspfNbr.from_json(json)
# print the JSON string representation of the object
print(RoutingOspfNbr.to_json())

# convert the object into a dict
routing_ospf_nbr_dict = routing_ospf_nbr_instance.to_dict()
# create an instance of RoutingOspfNbr from a dict
routing_ospf_nbr_from_dict = RoutingOspfNbr.from_dict(routing_ospf_nbr_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


