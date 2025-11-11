# ManaV2AppIdentifier


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**id** | **int** |  | [optional] 
**type** | **str** |  | [optional] 

## Example

```python
from graphiant_sdk.models.mana_v2_app_identifier import ManaV2AppIdentifier

# TODO update the JSON string below
json = "{}"
# create an instance of ManaV2AppIdentifier from a JSON string
mana_v2_app_identifier_instance = ManaV2AppIdentifier.from_json(json)
# print the JSON string representation of the object
print(ManaV2AppIdentifier.to_json())

# convert the object into a dict
mana_v2_app_identifier_dict = mana_v2_app_identifier_instance.to_dict()
# create an instance of ManaV2AppIdentifier from a dict
mana_v2_app_identifier_from_dict = ManaV2AppIdentifier.from_dict(mana_v2_app_identifier_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


