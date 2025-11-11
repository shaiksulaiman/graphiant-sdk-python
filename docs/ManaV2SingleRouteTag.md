# ManaV2SingleRouteTag


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**level_one** | [**ManaV2SingleRouteTagRouteTagElement**](ManaV2SingleRouteTagRouteTagElement.md) |  | [optional] 
**level_two** | [**ManaV2SingleRouteTagRouteTagElement**](ManaV2SingleRouteTagRouteTagElement.md) |  | [optional] 
**level_zero** | [**ManaV2SingleRouteTagRouteTagElement**](ManaV2SingleRouteTagRouteTagElement.md) |  | [optional] 

## Example

```python
from graphiant_sdk.models.mana_v2_single_route_tag import ManaV2SingleRouteTag

# TODO update the JSON string below
json = "{}"
# create an instance of ManaV2SingleRouteTag from a JSON string
mana_v2_single_route_tag_instance = ManaV2SingleRouteTag.from_json(json)
# print the JSON string representation of the object
print(ManaV2SingleRouteTag.to_json())

# convert the object into a dict
mana_v2_single_route_tag_dict = mana_v2_single_route_tag_instance.to_dict()
# create an instance of ManaV2SingleRouteTag from a dict
mana_v2_single_route_tag_from_dict = ManaV2SingleRouteTag.from_dict(mana_v2_single_route_tag_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


