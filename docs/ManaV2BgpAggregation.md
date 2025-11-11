# ManaV2BgpAggregation


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**as_set** | **bool** |  | [optional] 
**id** | **int** |  | [optional] 
**prefix** | **str** |  | [optional] 
**summary_only** | **bool** |  | [optional] 

## Example

```python
from graphiant_sdk.models.mana_v2_bgp_aggregation import ManaV2BgpAggregation

# TODO update the JSON string below
json = "{}"
# create an instance of ManaV2BgpAggregation from a JSON string
mana_v2_bgp_aggregation_instance = ManaV2BgpAggregation.from_json(json)
# print the JSON string representation of the object
print(ManaV2BgpAggregation.to_json())

# convert the object into a dict
mana_v2_bgp_aggregation_dict = mana_v2_bgp_aggregation_instance.to_dict()
# create an instance of ManaV2BgpAggregation from a dict
mana_v2_bgp_aggregation_from_dict = ManaV2BgpAggregation.from_dict(mana_v2_bgp_aggregation_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


