# ManaV2PrometheusRuleGroupConfig


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**description** | **str** |  | [optional] 
**interval_seconds** | **int** |  | [optional] 
**name** | **str** |  | [optional] 
**rules** | [**Dict[str, ManaV2NullablePrometheusRuleConfig]**](ManaV2NullablePrometheusRuleConfig.md) |  | [optional] 

## Example

```python
from graphiant_sdk.models.mana_v2_prometheus_rule_group_config import ManaV2PrometheusRuleGroupConfig

# TODO update the JSON string below
json = "{}"
# create an instance of ManaV2PrometheusRuleGroupConfig from a JSON string
mana_v2_prometheus_rule_group_config_instance = ManaV2PrometheusRuleGroupConfig.from_json(json)
# print the JSON string representation of the object
print(ManaV2PrometheusRuleGroupConfig.to_json())

# convert the object into a dict
mana_v2_prometheus_rule_group_config_dict = mana_v2_prometheus_rule_group_config_instance.to_dict()
# create an instance of ManaV2PrometheusRuleGroupConfig from a dict
mana_v2_prometheus_rule_group_config_from_dict = ManaV2PrometheusRuleGroupConfig.from_dict(mana_v2_prometheus_rule_group_config_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


