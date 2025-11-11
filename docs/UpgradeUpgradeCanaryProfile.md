# UpgradeUpgradeCanaryProfile


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**action** | **str** |  | [optional] 
**name** | **str** |  | [optional] 
**occurrence** | [**UpgradeUpgradeOccurrence**](UpgradeUpgradeOccurrence.md) |  | [optional] 
**release** | **str** |  | [optional] 

## Example

```python
from graphiant_sdk.models.upgrade_upgrade_canary_profile import UpgradeUpgradeCanaryProfile

# TODO update the JSON string below
json = "{}"
# create an instance of UpgradeUpgradeCanaryProfile from a JSON string
upgrade_upgrade_canary_profile_instance = UpgradeUpgradeCanaryProfile.from_json(json)
# print the JSON string representation of the object
print(UpgradeUpgradeCanaryProfile.to_json())

# convert the object into a dict
upgrade_upgrade_canary_profile_dict = upgrade_upgrade_canary_profile_instance.to_dict()
# create an instance of UpgradeUpgradeCanaryProfile from a dict
upgrade_upgrade_canary_profile_from_dict = UpgradeUpgradeCanaryProfile.from_dict(upgrade_upgrade_canary_profile_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


