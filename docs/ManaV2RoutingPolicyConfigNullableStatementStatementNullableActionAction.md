# ManaV2RoutingPolicyConfigNullableStatementStatementNullableActionAction


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**administrative_distance** | [**ManaV2NullableAdministrativeDistance**](ManaV2NullableAdministrativeDistance.md) |  | [optional] 
**aspath_prepend** | [**ManaV2NullableAsPathPrepend**](ManaV2NullableAsPathPrepend.md) |  | [optional] 
**bgp_set_next_hop** | [**ManaV2NullableBgpSetNextHop**](ManaV2NullableBgpSetNextHop.md) |  | [optional] 
**call_policy** | [**ManaV2NullableCallPolicy**](ManaV2NullableCallPolicy.md) |  | [optional] 
**communities** | [**ManaV2NullableCommunities**](ManaV2NullableCommunities.md) |  | [optional] 
**local_pref** | [**ManaV2NullableLocalPreferance**](ManaV2NullableLocalPreferance.md) |  | [optional] 
**metric** | [**ManaV2NullableMetric**](ManaV2NullableMetric.md) |  | [optional] 
**result** | **str** |  | [optional] 
**seq** | **int** |  | [optional] 
**weight** | [**ManaV2NullableWeight**](ManaV2NullableWeight.md) |  | [optional] 

## Example

```python
from graphiant_sdk.models.mana_v2_routing_policy_config_nullable_statement_statement_nullable_action_action import ManaV2RoutingPolicyConfigNullableStatementStatementNullableActionAction

# TODO update the JSON string below
json = "{}"
# create an instance of ManaV2RoutingPolicyConfigNullableStatementStatementNullableActionAction from a JSON string
mana_v2_routing_policy_config_nullable_statement_statement_nullable_action_action_instance = ManaV2RoutingPolicyConfigNullableStatementStatementNullableActionAction.from_json(json)
# print the JSON string representation of the object
print(ManaV2RoutingPolicyConfigNullableStatementStatementNullableActionAction.to_json())

# convert the object into a dict
mana_v2_routing_policy_config_nullable_statement_statement_nullable_action_action_dict = mana_v2_routing_policy_config_nullable_statement_statement_nullable_action_action_instance.to_dict()
# create an instance of ManaV2RoutingPolicyConfigNullableStatementStatementNullableActionAction from a dict
mana_v2_routing_policy_config_nullable_statement_statement_nullable_action_action_from_dict = ManaV2RoutingPolicyConfigNullableStatementStatementNullableActionAction.from_dict(mana_v2_routing_policy_config_nullable_statement_statement_nullable_action_action_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


