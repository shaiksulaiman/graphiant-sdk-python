# RoutingNbrStats


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**prefix_rcvd** | **int** | Prefixes received (required) | [optional] 

## Example

```python
from graphiant_sdk.models.routing_nbr_stats import RoutingNbrStats

# TODO update the JSON string below
json = "{}"
# create an instance of RoutingNbrStats from a JSON string
routing_nbr_stats_instance = RoutingNbrStats.from_json(json)
# print the JSON string representation of the object
print(RoutingNbrStats.to_json())

# convert the object into a dict
routing_nbr_stats_dict = routing_nbr_stats_instance.to_dict()
# create an instance of RoutingNbrStats from a dict
routing_nbr_stats_from_dict = RoutingNbrStats.from_dict(routing_nbr_stats_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


