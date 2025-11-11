# ManaV2RouteTagDevice


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**device_id** | **int** |  | [optional] 
**location_id** | **int** |  | [optional] 
**site_id** | **int** |  | [optional] 
**tag** | [**ManaV2RouteTag**](ManaV2RouteTag.md) |  | [optional] 

## Example

```python
from graphiant_sdk.models.mana_v2_route_tag_device import ManaV2RouteTagDevice

# TODO update the JSON string below
json = "{}"
# create an instance of ManaV2RouteTagDevice from a JSON string
mana_v2_route_tag_device_instance = ManaV2RouteTagDevice.from_json(json)
# print the JSON string representation of the object
print(ManaV2RouteTagDevice.to_json())

# convert the object into a dict
mana_v2_route_tag_device_dict = mana_v2_route_tag_device_instance.to_dict()
# create an instance of ManaV2RouteTagDevice from a dict
mana_v2_route_tag_device_from_dict = ManaV2RouteTagDevice.from_dict(mana_v2_route_tag_device_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


