# UpgradeSwVersion


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**name** | **str** |  | [optional] 
**release** | **str** |  | [optional] 
**version** | **str** |  | [optional] 

## Example

```python
from graphiant_sdk.models.upgrade_sw_version import UpgradeSwVersion

# TODO update the JSON string below
json = "{}"
# create an instance of UpgradeSwVersion from a JSON string
upgrade_sw_version_instance = UpgradeSwVersion.from_json(json)
# print the JSON string representation of the object
print(UpgradeSwVersion.to_json())

# convert the object into a dict
upgrade_sw_version_dict = upgrade_sw_version_instance.to_dict()
# create an instance of UpgradeSwVersion from a dict
upgrade_sw_version_from_dict = UpgradeSwVersion.from_dict(upgrade_sw_version_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


