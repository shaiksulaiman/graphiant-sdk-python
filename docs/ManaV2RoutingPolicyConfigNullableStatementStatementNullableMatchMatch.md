# ManaV2RoutingPolicyConfigNullableStatementStatementNullableMatchMatch


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**community** | [**ManaV2NullableCommunity**](ManaV2NullableCommunity.md) |  | [optional] 
**prefix_set** | [**ManaV2NullablePrefixSet**](ManaV2NullablePrefixSet.md) |  | [optional] 
**protocol_route_type** | [**ManaV2NullableProtocolRouteType**](ManaV2NullableProtocolRouteType.md) |  | [optional] 
**route_tag** | [**ManaV2NullableRouteTagSet**](ManaV2NullableRouteTagSet.md) |  | [optional] 
**seq** | **int** |  | [optional] 
**source_interface** | [**ManaV2NullableInterfaceName**](ManaV2NullableInterfaceName.md) |  | [optional] 
**source_protocol** | [**ManaV2NullableRoutingProtocol**](ManaV2NullableRoutingProtocol.md) |  | [optional] 
**stale** | [**ManaV2NullableStalePurge**](ManaV2NullableStalePurge.md) |  | [optional] 

## Example

```python
from graphiant_sdk.models.mana_v2_routing_policy_config_nullable_statement_statement_nullable_match_match import ManaV2RoutingPolicyConfigNullableStatementStatementNullableMatchMatch

# TODO update the JSON string below
json = "{}"
# create an instance of ManaV2RoutingPolicyConfigNullableStatementStatementNullableMatchMatch from a JSON string
mana_v2_routing_policy_config_nullable_statement_statement_nullable_match_match_instance = ManaV2RoutingPolicyConfigNullableStatementStatementNullableMatchMatch.from_json(json)
# print the JSON string representation of the object
print(ManaV2RoutingPolicyConfigNullableStatementStatementNullableMatchMatch.to_json())

# convert the object into a dict
mana_v2_routing_policy_config_nullable_statement_statement_nullable_match_match_dict = mana_v2_routing_policy_config_nullable_statement_statement_nullable_match_match_instance.to_dict()
# create an instance of ManaV2RoutingPolicyConfigNullableStatementStatementNullableMatchMatch from a dict
mana_v2_routing_policy_config_nullable_statement_statement_nullable_match_match_from_dict = ManaV2RoutingPolicyConfigNullableStatementStatementNullableMatchMatch.from_dict(mana_v2_routing_policy_config_nullable_statement_statement_nullable_match_match_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


