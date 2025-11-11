# ManaV2ManaConfiguration


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**mana_device** | [**ManaV2Device**](ManaV2Device.md) |  | [optional] 
**version_info** | [**ManaV2VersionMetadata**](ManaV2VersionMetadata.md) |  | [optional] 

## Example

```python
from graphiant_sdk.models.mana_v2_mana_configuration import ManaV2ManaConfiguration

# TODO update the JSON string below
json = "{}"
# create an instance of ManaV2ManaConfiguration from a JSON string
mana_v2_mana_configuration_instance = ManaV2ManaConfiguration.from_json(json)
# print the JSON string representation of the object
print(ManaV2ManaConfiguration.to_json())

# convert the object into a dict
mana_v2_mana_configuration_dict = mana_v2_mana_configuration_instance.to_dict()
# create an instance of ManaV2ManaConfiguration from a dict
mana_v2_mana_configuration_from_dict = ManaV2ManaConfiguration.from_dict(mana_v2_mana_configuration_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


