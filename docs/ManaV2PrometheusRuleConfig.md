# ManaV2PrometheusRuleConfig


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**alert** | **bool** |  | [optional] 
**expression** | **str** |  | [optional] 
**name** | **str** |  | [optional] 
**severity** | **str** |  | [optional] 
**template** | **str** |  | [optional] 
**trigger_seconds** | **int** |  | [optional] 

## Example

```python
from graphiant_sdk.models.mana_v2_prometheus_rule_config import ManaV2PrometheusRuleConfig

# TODO update the JSON string below
json = "{}"
# create an instance of ManaV2PrometheusRuleConfig from a JSON string
mana_v2_prometheus_rule_config_instance = ManaV2PrometheusRuleConfig.from_json(json)
# print the JSON string representation of the object
print(ManaV2PrometheusRuleConfig.to_json())

# convert the object into a dict
mana_v2_prometheus_rule_config_dict = mana_v2_prometheus_rule_config_instance.to_dict()
# create an instance of ManaV2PrometheusRuleConfig from a dict
mana_v2_prometheus_rule_config_from_dict = ManaV2PrometheusRuleConfig.from_dict(mana_v2_prometheus_rule_config_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


