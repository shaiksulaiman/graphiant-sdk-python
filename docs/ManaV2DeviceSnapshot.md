# ManaV2DeviceSnapshot


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**author** | [**CommonUserInfo**](CommonUserInfo.md) |  | [optional] 
**category** | **str** |  | [optional] 
**created_on** | [**GoogleProtobufTimestamp**](GoogleProtobufTimestamp.md) |  | [optional] 
**data** | [**ManaV2DeviceSnapshotData**](ManaV2DeviceSnapshotData.md) |  | [optional] 
**golden** | **bool** |  | [optional] 
**id** | **int** |  | [optional] 
**name** | **str** | name for the snapshot | [optional] 

## Example

```python
from graphiant_sdk.models.mana_v2_device_snapshot import ManaV2DeviceSnapshot

# TODO update the JSON string below
json = "{}"
# create an instance of ManaV2DeviceSnapshot from a JSON string
mana_v2_device_snapshot_instance = ManaV2DeviceSnapshot.from_json(json)
# print the JSON string representation of the object
print(ManaV2DeviceSnapshot.to_json())

# convert the object into a dict
mana_v2_device_snapshot_dict = mana_v2_device_snapshot_instance.to_dict()
# create an instance of ManaV2DeviceSnapshot from a dict
mana_v2_device_snapshot_from_dict = ManaV2DeviceSnapshot.from_dict(mana_v2_device_snapshot_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


