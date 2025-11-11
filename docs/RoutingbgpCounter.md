# RoutingbgpCounter


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**graceful_restart** | **int** |  | [optional] 
**local_as_number** | **int** |  | [optional] 
**local_ip_address** | **str** |  | [optional] 
**local_router_id** | **str** |  | [optional] 
**peer_router_id** | **str** |  | [optional] 
**up_time** | **str** |  | [optional] 

## Example

```python
from graphiant_sdk.models.routingbgp_counter import RoutingbgpCounter

# TODO update the JSON string below
json = "{}"
# create an instance of RoutingbgpCounter from a JSON string
routingbgp_counter_instance = RoutingbgpCounter.from_json(json)
# print the JSON string representation of the object
print(RoutingbgpCounter.to_json())

# convert the object into a dict
routingbgp_counter_dict = routingbgp_counter_instance.to_dict()
# create an instance of RoutingbgpCounter from a dict
routingbgp_counter_from_dict = RoutingbgpCounter.from_dict(routingbgp_counter_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


