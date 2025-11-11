# ManaV2VersionMetadata


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**id** | **int** |  | [optional] 
**name** | **str** |  | [optional] 
**version** | **int** |  | [optional] 

## Example

```python
from graphiant_sdk.models.mana_v2_version_metadata import ManaV2VersionMetadata

# TODO update the JSON string below
json = "{}"
# create an instance of ManaV2VersionMetadata from a JSON string
mana_v2_version_metadata_instance = ManaV2VersionMetadata.from_json(json)
# print the JSON string representation of the object
print(ManaV2VersionMetadata.to_json())

# convert the object into a dict
mana_v2_version_metadata_dict = mana_v2_version_metadata_instance.to_dict()
# create an instance of ManaV2VersionMetadata from a dict
mana_v2_version_metadata_from_dict = ManaV2VersionMetadata.from_dict(mana_v2_version_metadata_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


