# ManaV2ApplicationMatchConfig


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**builtin** | **str** |  | [optional] 
**custom** | **str** |  | [optional] 

## Example

```python
from graphiant_sdk.models.mana_v2_application_match_config import ManaV2ApplicationMatchConfig

# TODO update the JSON string below
json = "{}"
# create an instance of ManaV2ApplicationMatchConfig from a JSON string
mana_v2_application_match_config_instance = ManaV2ApplicationMatchConfig.from_json(json)
# print the JSON string representation of the object
print(ManaV2ApplicationMatchConfig.to_json())

# convert the object into a dict
mana_v2_application_match_config_dict = mana_v2_application_match_config_instance.to_dict()
# create an instance of ManaV2ApplicationMatchConfig from a dict
mana_v2_application_match_config_from_dict = ManaV2ApplicationMatchConfig.from_dict(mana_v2_application_match_config_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


