# ManaV2RoutingPolicyStatementAction


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**administrative_distance** | **int** |  | [optional] 
**aspath_prepend** | **int** |  | [optional] 
**bgp_set_next_hop** | **str** |  | [optional] 
**call_policy** | **str** |  | [optional] 
**community** | [**ManaV2CommunityType**](ManaV2CommunityType.md) |  | [optional] 
**id** | **int** |  | [optional] 
**local_pref** | **int** |  | [optional] 
**metric_absolute** | **int** |  | [optional] 
**metric_modifier** | **int** |  | [optional] 
**result** | **str** |  | [optional] 
**seq** | **int** |  | [optional] 
**weight** | **int** |  | [optional] 

## Example

```python
from graphiant_sdk.models.mana_v2_routing_policy_statement_action import ManaV2RoutingPolicyStatementAction

# TODO update the JSON string below
json = "{}"
# create an instance of ManaV2RoutingPolicyStatementAction from a JSON string
mana_v2_routing_policy_statement_action_instance = ManaV2RoutingPolicyStatementAction.from_json(json)
# print the JSON string representation of the object
print(ManaV2RoutingPolicyStatementAction.to_json())

# convert the object into a dict
mana_v2_routing_policy_statement_action_dict = mana_v2_routing_policy_statement_action_instance.to_dict()
# create an instance of ManaV2RoutingPolicyStatementAction from a dict
mana_v2_routing_policy_statement_action_from_dict = ManaV2RoutingPolicyStatementAction.from_dict(mana_v2_routing_policy_statement_action_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


