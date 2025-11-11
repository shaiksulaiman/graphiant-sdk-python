# ManaV2GlobalAppConfig


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**description** | **str** |  | [optional] 
**ip_lists** | **List[str]** |  | [optional] 
**ip_prefixes** | **List[str]** |  | [optional] 
**ip_protocol** | **str** |  | [optional] 
**name** | **str** |  | [optional] 
**port_ranges** | [**List[ManaV2GlobalAppPortRange]**](ManaV2GlobalAppPortRange.md) |  | [optional] 
**url** | **str** |  | [optional] 

## Example

```python
from graphiant_sdk.models.mana_v2_global_app_config import ManaV2GlobalAppConfig

# TODO update the JSON string below
json = "{}"
# create an instance of ManaV2GlobalAppConfig from a JSON string
mana_v2_global_app_config_instance = ManaV2GlobalAppConfig.from_json(json)
# print the JSON string representation of the object
print(ManaV2GlobalAppConfig.to_json())

# convert the object into a dict
mana_v2_global_app_config_dict = mana_v2_global_app_config_instance.to_dict()
# create an instance of ManaV2GlobalAppConfig from a dict
mana_v2_global_app_config_from_dict = ManaV2GlobalAppConfig.from_dict(mana_v2_global_app_config_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


