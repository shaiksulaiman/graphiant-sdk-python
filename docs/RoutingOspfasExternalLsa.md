# RoutingOspfasExternalLsa


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**forwarding_address** | **str** |  | [optional] 
**metric** | **int** |  | [optional] 
**metric_type** | **str** |  | [optional] 
**network_mask** | **int** |  | [optional] 
**tag** | **int** |  | [optional] 
**tos_metric** | [**RoutingOspflsaTosMetric**](RoutingOspflsaTosMetric.md) |  | [optional] 

## Example

```python
from graphiant_sdk.models.routing_ospfas_external_lsa import RoutingOspfasExternalLsa

# TODO update the JSON string below
json = "{}"
# create an instance of RoutingOspfasExternalLsa from a JSON string
routing_ospfas_external_lsa_instance = RoutingOspfasExternalLsa.from_json(json)
# print the JSON string representation of the object
print(RoutingOspfasExternalLsa.to_json())

# convert the object into a dict
routing_ospfas_external_lsa_dict = routing_ospfas_external_lsa_instance.to_dict()
# create an instance of RoutingOspfasExternalLsa from a dict
routing_ospfas_external_lsa_from_dict = RoutingOspfasExternalLsa.from_dict(routing_ospfas_external_lsa_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


