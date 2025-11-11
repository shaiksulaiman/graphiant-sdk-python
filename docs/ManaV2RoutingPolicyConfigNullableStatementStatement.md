# ManaV2RoutingPolicyConfigNullableStatementStatement


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**actions** | [**Dict[str, ManaV2RoutingPolicyConfigNullableStatementStatementNullableAction]**](ManaV2RoutingPolicyConfigNullableStatementStatementNullableAction.md) |  | [optional] 
**matches** | [**Dict[str, ManaV2RoutingPolicyConfigNullableStatementStatementNullableMatch]**](ManaV2RoutingPolicyConfigNullableStatementStatementNullableMatch.md) |  | [optional] 
**seq** | **int** |  | [optional] 

## Example

```python
from graphiant_sdk.models.mana_v2_routing_policy_config_nullable_statement_statement import ManaV2RoutingPolicyConfigNullableStatementStatement

# TODO update the JSON string below
json = "{}"
# create an instance of ManaV2RoutingPolicyConfigNullableStatementStatement from a JSON string
mana_v2_routing_policy_config_nullable_statement_statement_instance = ManaV2RoutingPolicyConfigNullableStatementStatement.from_json(json)
# print the JSON string representation of the object
print(ManaV2RoutingPolicyConfigNullableStatementStatement.to_json())

# convert the object into a dict
mana_v2_routing_policy_config_nullable_statement_statement_dict = mana_v2_routing_policy_config_nullable_statement_statement_instance.to_dict()
# create an instance of ManaV2RoutingPolicyConfigNullableStatementStatement from a dict
mana_v2_routing_policy_config_nullable_statement_statement_from_dict = ManaV2RoutingPolicyConfigNullableStatementStatement.from_dict(mana_v2_routing_policy_config_nullable_statement_statement_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


