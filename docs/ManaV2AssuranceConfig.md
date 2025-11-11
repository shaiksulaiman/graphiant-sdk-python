# ManaV2AssuranceConfig


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**apps** | [**List[ManaV2BucketApp]**](ManaV2BucketApp.md) |  | [optional] 
**flex_algo** | **str** |  | [optional] 
**lan_names** | **List[str]** |  | [optional] 
**name** | **str** |  | [optional] 
**site_list_id** | **int** |  | [optional] 
**use_all_sites** | **bool** |  | [optional] 

## Example

```python
from graphiant_sdk.models.mana_v2_assurance_config import ManaV2AssuranceConfig

# TODO update the JSON string below
json = "{}"
# create an instance of ManaV2AssuranceConfig from a JSON string
mana_v2_assurance_config_instance = ManaV2AssuranceConfig.from_json(json)
# print the JSON string representation of the object
print(ManaV2AssuranceConfig.to_json())

# convert the object into a dict
mana_v2_assurance_config_dict = mana_v2_assurance_config_instance.to_dict()
# create an instance of ManaV2AssuranceConfig from a dict
mana_v2_assurance_config_from_dict = ManaV2AssuranceConfig.from_dict(mana_v2_assurance_config_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


