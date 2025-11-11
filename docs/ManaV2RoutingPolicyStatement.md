# ManaV2RoutingPolicyStatement


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**actions** | [**List[ManaV2RoutingPolicyStatementAction]**](ManaV2RoutingPolicyStatementAction.md) |  | [optional] 
**id** | **int** |  | [optional] 
**matches** | [**List[ManaV2RoutingPolicyStatementMatch]**](ManaV2RoutingPolicyStatementMatch.md) |  | [optional] 
**seq** | **int** |  | [optional] 

## Example

```python
from graphiant_sdk.models.mana_v2_routing_policy_statement import ManaV2RoutingPolicyStatement

# TODO update the JSON string below
json = "{}"
# create an instance of ManaV2RoutingPolicyStatement from a JSON string
mana_v2_routing_policy_statement_instance = ManaV2RoutingPolicyStatement.from_json(json)
# print the JSON string representation of the object
print(ManaV2RoutingPolicyStatement.to_json())

# convert the object into a dict
mana_v2_routing_policy_statement_dict = mana_v2_routing_policy_statement_instance.to_dict()
# create an instance of ManaV2RoutingPolicyStatement from a dict
mana_v2_routing_policy_statement_from_dict = ManaV2RoutingPolicyStatement.from_dict(mana_v2_routing_policy_statement_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


