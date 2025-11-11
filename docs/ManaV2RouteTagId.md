# ManaV2RouteTagId


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**level_one** | **int** |  | [optional] 
**level_two** | **int** |  | [optional] 
**level_zero** | **int** |  | [optional] 

## Example

```python
from graphiant_sdk.models.mana_v2_route_tag_id import ManaV2RouteTagId

# TODO update the JSON string below
json = "{}"
# create an instance of ManaV2RouteTagId from a JSON string
mana_v2_route_tag_id_instance = ManaV2RouteTagId.from_json(json)
# print the JSON string representation of the object
print(ManaV2RouteTagId.to_json())

# convert the object into a dict
mana_v2_route_tag_id_dict = mana_v2_route_tag_id_instance.to_dict()
# create an instance of ManaV2RouteTagId from a dict
mana_v2_route_tag_id_from_dict = ManaV2RouteTagId.from_dict(mana_v2_route_tag_id_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


