# ManaV2CoreLinkCost


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**dynamic** | [**ManaV2LatencyBandwidth**](ManaV2LatencyBandwidth.md) |  | [optional] 
**static** | **int** |  | [optional] 

## Example

```python
from graphiant_sdk.models.mana_v2_core_link_cost import ManaV2CoreLinkCost

# TODO update the JSON string below
json = "{}"
# create an instance of ManaV2CoreLinkCost from a JSON string
mana_v2_core_link_cost_instance = ManaV2CoreLinkCost.from_json(json)
# print the JSON string representation of the object
print(ManaV2CoreLinkCost.to_json())

# convert the object into a dict
mana_v2_core_link_cost_dict = mana_v2_core_link_cost_instance.to_dict()
# create an instance of ManaV2CoreLinkCost from a dict
mana_v2_core_link_cost_from_dict = ManaV2CoreLinkCost.from_dict(mana_v2_core_link_cost_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


