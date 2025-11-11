# ManaV2RoutingPolicyConfig


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**attach_point** | **str** |  | [optional] 
**default_action** | **str** |  | [optional] 
**description** | **str** |  | [optional] 
**global_id** | **int** |  | [optional] 
**is_global_sync** | **bool** |  | [optional] 
**name** | **str** |  | [optional] 
**statements** | [**Dict[str, ManaV2RoutingPolicyConfigNullableStatement]**](ManaV2RoutingPolicyConfigNullableStatement.md) |  | [optional] 

## Example

```python
from graphiant_sdk.models.mana_v2_routing_policy_config import ManaV2RoutingPolicyConfig

# TODO update the JSON string below
json = "{}"
# create an instance of ManaV2RoutingPolicyConfig from a JSON string
mana_v2_routing_policy_config_instance = ManaV2RoutingPolicyConfig.from_json(json)
# print the JSON string representation of the object
print(ManaV2RoutingPolicyConfig.to_json())

# convert the object into a dict
mana_v2_routing_policy_config_dict = mana_v2_routing_policy_config_instance.to_dict()
# create an instance of ManaV2RoutingPolicyConfig from a dict
mana_v2_routing_policy_config_from_dict = ManaV2RoutingPolicyConfig.from_dict(mana_v2_routing_policy_config_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


