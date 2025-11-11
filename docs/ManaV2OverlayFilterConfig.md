# ManaV2OverlayFilterConfig


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**export_policy** | [**ManaV2NullablePolicyName**](ManaV2NullablePolicyName.md) |  | [optional] 
**import_policy** | [**ManaV2NullablePolicyName**](ManaV2NullablePolicyName.md) |  | [optional] 

## Example

```python
from graphiant_sdk.models.mana_v2_overlay_filter_config import ManaV2OverlayFilterConfig

# TODO update the JSON string below
json = "{}"
# create an instance of ManaV2OverlayFilterConfig from a JSON string
mana_v2_overlay_filter_config_instance = ManaV2OverlayFilterConfig.from_json(json)
# print the JSON string representation of the object
print(ManaV2OverlayFilterConfig.to_json())

# convert the object into a dict
mana_v2_overlay_filter_config_dict = mana_v2_overlay_filter_config_instance.to_dict()
# create an instance of ManaV2OverlayFilterConfig from a dict
mana_v2_overlay_filter_config_from_dict = ManaV2OverlayFilterConfig.from_dict(mana_v2_overlay_filter_config_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


