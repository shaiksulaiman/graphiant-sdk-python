# ManaV2DeviceSnapshotData


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**ospf_installed_route_count** | **int** |  | [optional] 
**t2_session_count** | **int** |  | [optional] 
**twamp_session_count** | **int** |  | [optional] 
**bfd_session_count** | **int** |  | [optional] 
**bgp_neighbor_ip_list** | **List[str]** |  | [optional] 
**bgp_session_count** | **int** |  | [optional] 
**device_role** | **str** |  | [optional] 
**failed_services_count** | **int** |  | [optional] 
**graphnos_version** | **str** |  | [optional] 
**installed_labels** | **int** |  | [optional] 
**ipsec_session_count** | **int** |  | [optional] 
**ongoing_alerts** | **int** |  | [optional] 
**ospf_neighbor_ip_list** | **List[str]** |  | [optional] 
**ospf_session_count** | **int** |  | [optional] 

## Example

```python
from graphiant_sdk.models.mana_v2_device_snapshot_data import ManaV2DeviceSnapshotData

# TODO update the JSON string below
json = "{}"
# create an instance of ManaV2DeviceSnapshotData from a JSON string
mana_v2_device_snapshot_data_instance = ManaV2DeviceSnapshotData.from_json(json)
# print the JSON string representation of the object
print(ManaV2DeviceSnapshotData.to_json())

# convert the object into a dict
mana_v2_device_snapshot_data_dict = mana_v2_device_snapshot_data_instance.to_dict()
# create an instance of ManaV2DeviceSnapshotData from a dict
mana_v2_device_snapshot_data_from_dict = ManaV2DeviceSnapshotData.from_dict(mana_v2_device_snapshot_data_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


