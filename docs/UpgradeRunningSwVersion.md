# UpgradeRunningSwVersion


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**device_id** | **int** |  | [optional] 
**version** | [**UpgradeSwVersion**](UpgradeSwVersion.md) |  | [optional] 

## Example

```python
from graphiant_sdk.models.upgrade_running_sw_version import UpgradeRunningSwVersion

# TODO update the JSON string below
json = "{}"
# create an instance of UpgradeRunningSwVersion from a JSON string
upgrade_running_sw_version_instance = UpgradeRunningSwVersion.from_json(json)
# print the JSON string representation of the object
print(UpgradeRunningSwVersion.to_json())

# convert the object into a dict
upgrade_running_sw_version_dict = upgrade_running_sw_version_instance.to_dict()
# create an instance of UpgradeRunningSwVersion from a dict
upgrade_running_sw_version_from_dict = UpgradeRunningSwVersion.from_dict(upgrade_running_sw_version_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


