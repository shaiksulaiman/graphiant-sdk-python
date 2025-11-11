# ManaV2DeviceSnapshotList


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**count** | **int** |  | [optional] 
**snapshots** | [**List[ManaV2DeviceSnapshot]**](ManaV2DeviceSnapshot.md) |  | [optional] 

## Example

```python
from graphiant_sdk.models.mana_v2_device_snapshot_list import ManaV2DeviceSnapshotList

# TODO update the JSON string below
json = "{}"
# create an instance of ManaV2DeviceSnapshotList from a JSON string
mana_v2_device_snapshot_list_instance = ManaV2DeviceSnapshotList.from_json(json)
# print the JSON string representation of the object
print(ManaV2DeviceSnapshotList.to_json())

# convert the object into a dict
mana_v2_device_snapshot_list_dict = mana_v2_device_snapshot_list_instance.to_dict()
# create an instance of ManaV2DeviceSnapshotList from a dict
mana_v2_device_snapshot_list_from_dict = ManaV2DeviceSnapshotList.from_dict(mana_v2_device_snapshot_list_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


