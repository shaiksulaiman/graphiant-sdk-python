# ManaV2Zone


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**enterprise_id** | **int** |  | [optional] 
**id** | **int** |  | [optional] 
**name** | **str** |  | [optional] 

## Example

```python
from graphiant_sdk.models.mana_v2_zone import ManaV2Zone

# TODO update the JSON string below
json = "{}"
# create an instance of ManaV2Zone from a JSON string
mana_v2_zone_instance = ManaV2Zone.from_json(json)
# print the JSON string representation of the object
print(ManaV2Zone.to_json())

# convert the object into a dict
mana_v2_zone_dict = mana_v2_zone_instance.to_dict()
# create an instance of ManaV2Zone from a dict
mana_v2_zone_from_dict = ManaV2Zone.from_dict(mana_v2_zone_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


