# RoutingOspflsa


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**advertising_router** | **str** | IP address (required) | [optional] 
**age** | **int** | How old is the LSA (required) | [optional] 
**asexternal_lsa** | [**RoutingOspfasExternalLsa**](RoutingOspfasExternalLsa.md) |  | [optional] 
**checksum** | **int** | LSA Checksum (required) | [optional] 
**length** | **int** | LSA length (required) | [optional] 
**link_id** | **str** | IP address of link on peer (required) | [optional] 
**network_lsa** | [**RoutingOspfNetworkLsa**](RoutingOspfNetworkLsa.md) |  | [optional] 
**router_lsa** | [**RoutingOspfRouterLsa**](RoutingOspfRouterLsa.md) |  | [optional] 
**sequence_number** | **str** | LSA sequence number (required) | [optional] 
**summary_lsa** | [**RoutingOspfSummaryLsa**](RoutingOspfSummaryLsa.md) |  | [optional] 
**type** | **str** | Type of LSA (required) | [optional] 

## Example

```python
from graphiant_sdk.models.routing_ospflsa import RoutingOspflsa

# TODO update the JSON string below
json = "{}"
# create an instance of RoutingOspflsa from a JSON string
routing_ospflsa_instance = RoutingOspflsa.from_json(json)
# print the JSON string representation of the object
print(RoutingOspflsa.to_json())

# convert the object into a dict
routing_ospflsa_dict = routing_ospflsa_instance.to_dict()
# create an instance of RoutingOspflsa from a dict
routing_ospflsa_from_dict = RoutingOspflsa.from_dict(routing_ospflsa_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


