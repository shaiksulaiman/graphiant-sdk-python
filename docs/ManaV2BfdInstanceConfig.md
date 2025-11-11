# ManaV2BfdInstanceConfig


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**enabled** | **bool** |  | [optional] 
**local_multiplier** | **int** |  | [optional] 
**minimum_interval** | **int** |  | [optional] 

## Example

```python
from graphiant_sdk.models.mana_v2_bfd_instance_config import ManaV2BfdInstanceConfig

# TODO update the JSON string below
json = "{}"
# create an instance of ManaV2BfdInstanceConfig from a JSON string
mana_v2_bfd_instance_config_instance = ManaV2BfdInstanceConfig.from_json(json)
# print the JSON string representation of the object
print(ManaV2BfdInstanceConfig.to_json())

# convert the object into a dict
mana_v2_bfd_instance_config_dict = mana_v2_bfd_instance_config_instance.to_dict()
# create an instance of ManaV2BfdInstanceConfig from a dict
mana_v2_bfd_instance_config_from_dict = ManaV2BfdInstanceConfig.from_dict(mana_v2_bfd_instance_config_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


