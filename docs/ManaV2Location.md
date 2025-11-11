# ManaV2Location


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**address_line1** | **str** |  | [optional] 
**address_line2** | **str** |  | [optional] 
**city** | **str** |  | [optional] 
**country** | **str** |  | [optional] 
**country_code** | **str** |  | [optional] 
**latitude** | **float** |  | [optional] 
**longitude** | **float** |  | [optional] 
**notes** | **str** |  | [optional] 
**province_code** | **str** |  | [optional] 
**state** | **str** |  | [optional] 
**state_code** | **str** |  | [optional] 

## Example

```python
from graphiant_sdk.models.mana_v2_location import ManaV2Location

# TODO update the JSON string below
json = "{}"
# create an instance of ManaV2Location from a JSON string
mana_v2_location_instance = ManaV2Location.from_json(json)
# print the JSON string representation of the object
print(ManaV2Location.to_json())

# convert the object into a dict
mana_v2_location_dict = mana_v2_location_instance.to_dict()
# create an instance of ManaV2Location from a dict
mana_v2_location_from_dict = ManaV2Location.from_dict(mana_v2_location_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


