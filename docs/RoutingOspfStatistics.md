# RoutingOspfStatistics


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**discontinuity_time** | **str** |  | [optional] 
**route_count** | **int** |  | [optional] 

## Example

```python
from graphiant_sdk.models.routing_ospf_statistics import RoutingOspfStatistics

# TODO update the JSON string below
json = "{}"
# create an instance of RoutingOspfStatistics from a JSON string
routing_ospf_statistics_instance = RoutingOspfStatistics.from_json(json)
# print the JSON string representation of the object
print(RoutingOspfStatistics.to_json())

# convert the object into a dict
routing_ospf_statistics_dict = routing_ospf_statistics_instance.to_dict()
# create an instance of RoutingOspfStatistics from a dict
routing_ospf_statistics_from_dict = RoutingOspfStatistics.from_dict(routing_ospf_statistics_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


