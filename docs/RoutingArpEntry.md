# RoutingArpEntry


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**interface_name** | **str** |  | [optional] 
**ipv4_address** | **str** |  | [optional] 
**mac_address** | **str** |  | [optional] 
**name** | **str** | Circuit or VRF name | [optional] 

## Example

```python
from graphiant_sdk.models.routing_arp_entry import RoutingArpEntry

# TODO update the JSON string below
json = "{}"
# create an instance of RoutingArpEntry from a JSON string
routing_arp_entry_instance = RoutingArpEntry.from_json(json)
# print the JSON string representation of the object
print(RoutingArpEntry.to_json())

# convert the object into a dict
routing_arp_entry_dict = routing_arp_entry_instance.to_dict()
# create an instance of RoutingArpEntry from a dict
routing_arp_entry_from_dict = RoutingArpEntry.from_dict(routing_arp_entry_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


