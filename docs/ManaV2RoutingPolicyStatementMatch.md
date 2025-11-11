# ManaV2RoutingPolicyStatementMatch


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**community** | **List[str]** |  | [optional] 
**id** | **int** |  | [optional] 
**prefix_set** | **str** |  | [optional] 
**protocol_route_type** | **str** |  | [optional] 
**route_tag** | [**ManaV2RouteTag**](ManaV2RouteTag.md) |  | [optional] 
**seq** | **int** |  | [optional] 
**source_interface** | **str** |  | [optional] 
**source_protocol** | **str** |  | [optional] 
**stale_purge** | **bool** |  | [optional] 

## Example

```python
from graphiant_sdk.models.mana_v2_routing_policy_statement_match import ManaV2RoutingPolicyStatementMatch

# TODO update the JSON string below
json = "{}"
# create an instance of ManaV2RoutingPolicyStatementMatch from a JSON string
mana_v2_routing_policy_statement_match_instance = ManaV2RoutingPolicyStatementMatch.from_json(json)
# print the JSON string representation of the object
print(ManaV2RoutingPolicyStatementMatch.to_json())

# convert the object into a dict
mana_v2_routing_policy_statement_match_dict = mana_v2_routing_policy_statement_match_instance.to_dict()
# create an instance of ManaV2RoutingPolicyStatementMatch from a dict
mana_v2_routing_policy_statement_match_from_dict = ManaV2RoutingPolicyStatementMatch.from_dict(mana_v2_routing_policy_statement_match_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


