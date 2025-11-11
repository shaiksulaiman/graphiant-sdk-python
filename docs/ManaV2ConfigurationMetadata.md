# ManaV2ConfigurationMetadata


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**commit_confirm** | **bool** |  | [optional] 
**description** | **str** |  | [optional] 
**name** | **str** |  | [optional] 

## Example

```python
from graphiant_sdk.models.mana_v2_configuration_metadata import ManaV2ConfigurationMetadata

# TODO update the JSON string below
json = "{}"
# create an instance of ManaV2ConfigurationMetadata from a JSON string
mana_v2_configuration_metadata_instance = ManaV2ConfigurationMetadata.from_json(json)
# print the JSON string representation of the object
print(ManaV2ConfigurationMetadata.to_json())

# convert the object into a dict
mana_v2_configuration_metadata_dict = mana_v2_configuration_metadata_instance.to_dict()
# create an instance of ManaV2ConfigurationMetadata from a dict
mana_v2_configuration_metadata_from_dict = ManaV2ConfigurationMetadata.from_dict(mana_v2_configuration_metadata_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


