# RoutingVrrpEntry


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**address_family** | **str** | type of IP address | [optional] 
**advertisement_rcvd** | **int** |  | [optional] 
**advertisement_sent** | **int** |  | [optional] 
**effective_priority** | **int** |  | [optional] 
**group_id** | **int** |  | [optional] 
**is_owner** | **bool** |  | [optional] 
**master_transition** | **int** |  | [optional] 
**new_master_reason** | **str** |  | [optional] 
**priority_zero_pkts_rcvd** | **int** |  | [optional] 
**priority_zero_pkts_sent** | **int** |  | [optional] 
**state** | **str** |  | [optional] 

## Example

```python
from graphiant_sdk.models.routing_vrrp_entry import RoutingVrrpEntry

# TODO update the JSON string below
json = "{}"
# create an instance of RoutingVrrpEntry from a JSON string
routing_vrrp_entry_instance = RoutingVrrpEntry.from_json(json)
# print the JSON string representation of the object
print(RoutingVrrpEntry.to_json())

# convert the object into a dict
routing_vrrp_entry_dict = routing_vrrp_entry_instance.to_dict()
# create an instance of RoutingVrrpEntry from a dict
routing_vrrp_entry_from_dict = RoutingVrrpEntry.from_dict(routing_vrrp_entry_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


