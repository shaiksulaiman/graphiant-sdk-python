# ManaV2BgpAggregationsConfig


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**as_set** | **bool** |  | [optional] 
**prefix** | **str** |  | [optional] 
**summary_only** | **bool** |  | [optional] 

## Example

```python
from graphiant_sdk.models.mana_v2_bgp_aggregations_config import ManaV2BgpAggregationsConfig

# TODO update the JSON string below
json = "{}"
# create an instance of ManaV2BgpAggregationsConfig from a JSON string
mana_v2_bgp_aggregations_config_instance = ManaV2BgpAggregationsConfig.from_json(json)
# print the JSON string representation of the object
print(ManaV2BgpAggregationsConfig.to_json())

# convert the object into a dict
mana_v2_bgp_aggregations_config_dict = mana_v2_bgp_aggregations_config_instance.to_dict()
# create an instance of ManaV2BgpAggregationsConfig from a dict
mana_v2_bgp_aggregations_config_from_dict = ManaV2BgpAggregationsConfig.from_dict(mana_v2_bgp_aggregations_config_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


