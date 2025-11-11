# ManaV2App


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**description** | **str** |  | [optional] 
**identifier** | [**ManaV2AppIdentifier**](ManaV2AppIdentifier.md) |  | [optional] 
**name** | **str** |  | [optional] 

## Example

```python
from graphiant_sdk.models.mana_v2_app import ManaV2App

# TODO update the JSON string below
json = "{}"
# create an instance of ManaV2App from a JSON string
mana_v2_app_instance = ManaV2App.from_json(json)
# print the JSON string representation of the object
print(ManaV2App.to_json())

# convert the object into a dict
mana_v2_app_dict = mana_v2_app_instance.to_dict()
# create an instance of ManaV2App from a dict
mana_v2_app_from_dict = ManaV2App.from_dict(mana_v2_app_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


