# ManaV2OverlayFilters


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**inbound_filter** | **str** |  | [optional] 
**outbound_filter** | **str** |  | [optional] 

## Example

```python
from graphiant_sdk.models.mana_v2_overlay_filters import ManaV2OverlayFilters

# TODO update the JSON string below
json = "{}"
# create an instance of ManaV2OverlayFilters from a JSON string
mana_v2_overlay_filters_instance = ManaV2OverlayFilters.from_json(json)
# print the JSON string representation of the object
print(ManaV2OverlayFilters.to_json())

# convert the object into a dict
mana_v2_overlay_filters_dict = mana_v2_overlay_filters_instance.to_dict()
# create an instance of ManaV2OverlayFilters from a dict
mana_v2_overlay_filters_from_dict = ManaV2OverlayFilters.from_dict(mana_v2_overlay_filters_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


