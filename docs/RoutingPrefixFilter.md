# RoutingPrefixFilter


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**as_path** | **List[str]** |  | [optional] 
**ext_community** | **str** |  | [optional] 
**interface_name** | **str** | Interface name | [optional] 
**next_hop** | **str** | IPv4 or IPv6 Nexthop | [optional] 
**prefix** | **str** |  | [optional] 
**rd** | **str** | Route RD. Must for BGPAddrFamilyVpnIpv4Unicast/BGPAddrFamilyVpnIpv6Unicast | [optional] 
**src_proto** | **str** |  | [optional] 
**type** | **str** | route type | [optional] 

## Example

```python
from graphiant_sdk.models.routing_prefix_filter import RoutingPrefixFilter

# TODO update the JSON string below
json = "{}"
# create an instance of RoutingPrefixFilter from a JSON string
routing_prefix_filter_instance = RoutingPrefixFilter.from_json(json)
# print the JSON string representation of the object
print(RoutingPrefixFilter.to_json())

# convert the object into a dict
routing_prefix_filter_dict = routing_prefix_filter_instance.to_dict()
# create an instance of RoutingPrefixFilter from a dict
routing_prefix_filter_from_dict = RoutingPrefixFilter.from_dict(routing_prefix_filter_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


