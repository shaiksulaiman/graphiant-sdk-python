# UpgradeGcsReleaseDetails


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**category** | [**List[UpgradeGcsReleaseCategory]**](UpgradeGcsReleaseCategory.md) |  | [optional] 
**major** | **bool** |  | [optional] 
**release_ts** | [**GoogleProtobufTimestamp**](GoogleProtobufTimestamp.md) |  | [optional] 

## Example

```python
from graphiant_sdk.models.upgrade_gcs_release_details import UpgradeGcsReleaseDetails

# TODO update the JSON string below
json = "{}"
# create an instance of UpgradeGcsReleaseDetails from a JSON string
upgrade_gcs_release_details_instance = UpgradeGcsReleaseDetails.from_json(json)
# print the JSON string representation of the object
print(UpgradeGcsReleaseDetails.to_json())

# convert the object into a dict
upgrade_gcs_release_details_dict = upgrade_gcs_release_details_instance.to_dict()
# create an instance of UpgradeGcsReleaseDetails from a dict
upgrade_gcs_release_details_from_dict = UpgradeGcsReleaseDetails.from_dict(upgrade_gcs_release_details_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


