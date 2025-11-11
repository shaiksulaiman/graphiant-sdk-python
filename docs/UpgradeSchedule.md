# UpgradeSchedule


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**action** | **str** |  | [optional] 
**device_id** | **int** |  | [optional] 
**download_progress** | **int** |  | [optional] 
**failure_reason** | **str** |  | [optional] 
**state** | **str** |  | [optional] 
**ts** | [**GoogleProtobufTimestamp**](GoogleProtobufTimestamp.md) |  | [optional] 
**version** | [**UpgradeSwVersion**](UpgradeSwVersion.md) |  | [optional] 

## Example

```python
from graphiant_sdk.models.upgrade_schedule import UpgradeSchedule

# TODO update the JSON string below
json = "{}"
# create an instance of UpgradeSchedule from a JSON string
upgrade_schedule_instance = UpgradeSchedule.from_json(json)
# print the JSON string representation of the object
print(UpgradeSchedule.to_json())

# convert the object into a dict
upgrade_schedule_dict = upgrade_schedule_instance.to_dict()
# create an instance of UpgradeSchedule from a dict
upgrade_schedule_from_dict = UpgradeSchedule.from_dict(upgrade_schedule_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


