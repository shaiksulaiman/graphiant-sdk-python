# ManaV2LacpConfig


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**mode** | **str** |  | [optional] 
**timer** | **str** |  | [optional] 

## Example

```python
from graphiant_sdk.models.mana_v2_lacp_config import ManaV2LacpConfig

# TODO update the JSON string below
json = "{}"
# create an instance of ManaV2LacpConfig from a JSON string
mana_v2_lacp_config_instance = ManaV2LacpConfig.from_json(json)
# print the JSON string representation of the object
print(ManaV2LacpConfig.to_json())

# convert the object into a dict
mana_v2_lacp_config_dict = mana_v2_lacp_config_instance.to_dict()
# create an instance of ManaV2LacpConfig from a dict
mana_v2_lacp_config_from_dict = ManaV2LacpConfig.from_dict(mana_v2_lacp_config_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


