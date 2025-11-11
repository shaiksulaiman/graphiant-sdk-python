# UpgradeReleaseSummary


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**eos_ts** | [**GoogleProtobufTimestamp**](GoogleProtobufTimestamp.md) |  | [optional] 
**key** | [**UpgradeInventoryKey**](UpgradeInventoryKey.md) |  | [optional] 
**name** | **str** |  | [optional] 
**release** | **str** |  | [optional] 
**release_ts** | [**GoogleProtobufTimestamp**](GoogleProtobufTimestamp.md) |  | [optional] 

## Example

```python
from graphiant_sdk.models.upgrade_release_summary import UpgradeReleaseSummary

# TODO update the JSON string below
json = "{}"
# create an instance of UpgradeReleaseSummary from a JSON string
upgrade_release_summary_instance = UpgradeReleaseSummary.from_json(json)
# print the JSON string representation of the object
print(UpgradeReleaseSummary.to_json())

# convert the object into a dict
upgrade_release_summary_dict = upgrade_release_summary_instance.to_dict()
# create an instance of UpgradeReleaseSummary from a dict
upgrade_release_summary_from_dict = UpgradeReleaseSummary.from_dict(upgrade_release_summary_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


