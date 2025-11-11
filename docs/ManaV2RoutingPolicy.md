# ManaV2RoutingPolicy


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**attach_point** | **str** |  | [optional] 
**default_action** | **str** |  | [optional] 
**description** | **str** |  | [optional] 
**error_message** | **str** |  | [optional] 
**global_id** | **int** |  | [optional] 
**id** | **int** |  | [optional] 
**name** | **str** |  | [optional] 
**statements** | [**List[ManaV2RoutingPolicyStatement]**](ManaV2RoutingPolicyStatement.md) |  | [optional] 
**status** | **str** |  | [optional] 

## Example

```python
from graphiant_sdk.models.mana_v2_routing_policy import ManaV2RoutingPolicy

# TODO update the JSON string below
json = "{}"
# create an instance of ManaV2RoutingPolicy from a JSON string
mana_v2_routing_policy_instance = ManaV2RoutingPolicy.from_json(json)
# print the JSON string representation of the object
print(ManaV2RoutingPolicy.to_json())

# convert the object into a dict
mana_v2_routing_policy_dict = mana_v2_routing_policy_instance.to_dict()
# create an instance of ManaV2RoutingPolicy from a dict
mana_v2_routing_policy_from_dict = ManaV2RoutingPolicy.from_dict(mana_v2_routing_policy_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


