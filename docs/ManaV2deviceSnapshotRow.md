# ManaV2deviceSnapshotRow


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**device_id** | **int** |  | [optional] 
**hostname** | **str** |  | [optional] 
**region** | **str** |  | [optional] 
**site** | **str** |  | [optional] 
**snapshot_count** | **int** |  | [optional] 
**snapshots** | [**List[ManaV2DeviceSnapshot]**](ManaV2DeviceSnapshot.md) |  | [optional] 
**uptime** | [**GoogleProtobufDuration**](GoogleProtobufDuration.md) |  | [optional] 

## Example

```python
from graphiant_sdk.models.mana_v2device_snapshot_row import ManaV2deviceSnapshotRow

# TODO update the JSON string below
json = "{}"
# create an instance of ManaV2deviceSnapshotRow from a JSON string
mana_v2device_snapshot_row_instance = ManaV2deviceSnapshotRow.from_json(json)
# print the JSON string representation of the object
print(ManaV2deviceSnapshotRow.to_json())

# convert the object into a dict
mana_v2device_snapshot_row_dict = mana_v2device_snapshot_row_instance.to_dict()
# create an instance of ManaV2deviceSnapshotRow from a dict
mana_v2device_snapshot_row_from_dict = ManaV2deviceSnapshotRow.from_dict(mana_v2device_snapshot_row_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


