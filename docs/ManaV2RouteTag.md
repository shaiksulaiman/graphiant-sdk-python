# ManaV2RouteTag


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**level_one** | **str** |  | [optional] 
**level_two** | **str** |  | [optional] 
**level_zero** | **str** |  | [optional] 

## Example

```python
from graphiant_sdk.models.mana_v2_route_tag import ManaV2RouteTag

# TODO update the JSON string below
json = "{}"
# create an instance of ManaV2RouteTag from a JSON string
mana_v2_route_tag_instance = ManaV2RouteTag.from_json(json)
# print the JSON string representation of the object
print(ManaV2RouteTag.to_json())

# convert the object into a dict
mana_v2_route_tag_dict = mana_v2_route_tag_instance.to_dict()
# create an instance of ManaV2RouteTag from a dict
mana_v2_route_tag_from_dict = ManaV2RouteTag.from_dict(mana_v2_route_tag_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


