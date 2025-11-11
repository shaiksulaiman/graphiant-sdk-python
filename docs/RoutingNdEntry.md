# RoutingNdEntry


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**interface_name** | **str** |  | [optional] 
**ipv6_address** | **str** |  | [optional] 
**mac_address** | **str** |  | [optional] 
**name** | **str** | Circuit or VRF name | [optional] 

## Example

```python
from graphiant_sdk.models.routing_nd_entry import RoutingNdEntry

# TODO update the JSON string below
json = "{}"
# create an instance of RoutingNdEntry from a JSON string
routing_nd_entry_instance = RoutingNdEntry.from_json(json)
# print the JSON string representation of the object
print(RoutingNdEntry.to_json())

# convert the object into a dict
routing_nd_entry_dict = routing_nd_entry_instance.to_dict()
# create an instance of RoutingNdEntry from a dict
routing_nd_entry_from_dict = RoutingNdEntry.from_dict(routing_nd_entry_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


