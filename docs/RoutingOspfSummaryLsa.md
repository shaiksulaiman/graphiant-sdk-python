# RoutingOspfSummaryLsa


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**network_mask** | **int** |  | [optional] 
**tos_metric** | [**RoutingOspflsaTosMetric**](RoutingOspflsaTosMetric.md) |  | [optional] 

## Example

```python
from graphiant_sdk.models.routing_ospf_summary_lsa import RoutingOspfSummaryLsa

# TODO update the JSON string below
json = "{}"
# create an instance of RoutingOspfSummaryLsa from a JSON string
routing_ospf_summary_lsa_instance = RoutingOspfSummaryLsa.from_json(json)
# print the JSON string representation of the object
print(RoutingOspfSummaryLsa.to_json())

# convert the object into a dict
routing_ospf_summary_lsa_dict = routing_ospf_summary_lsa_instance.to_dict()
# create an instance of RoutingOspfSummaryLsa from a dict
routing_ospf_summary_lsa_from_dict = RoutingOspfSummaryLsa.from_dict(routing_ospf_summary_lsa_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


