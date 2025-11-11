# ManaV2AppListConfig


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**apps** | [**List[ManaV2AppIdentifier]**](ManaV2AppIdentifier.md) |  | [optional] 
**description** | **str** |  | [optional] 
**name** | **str** |  | [optional] 

## Example

```python
from graphiant_sdk.models.mana_v2_app_list_config import ManaV2AppListConfig

# TODO update the JSON string below
json = "{}"
# create an instance of ManaV2AppListConfig from a JSON string
mana_v2_app_list_config_instance = ManaV2AppListConfig.from_json(json)
# print the JSON string representation of the object
print(ManaV2AppListConfig.to_json())

# convert the object into a dict
mana_v2_app_list_config_dict = mana_v2_app_list_config_instance.to_dict()
# create an instance of ManaV2AppListConfig from a dict
mana_v2_app_list_config_from_dict = ManaV2AppListConfig.from_dict(mana_v2_app_list_config_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


