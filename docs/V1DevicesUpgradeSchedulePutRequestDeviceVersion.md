# V1DevicesUpgradeSchedulePutRequestDeviceVersion


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**device_id** | **int** |  | [optional] 
**version** | [**UpgradeSwVersion**](UpgradeSwVersion.md) |  | [optional] 

## Example

```python
from graphiant_sdk.models.v1_devices_upgrade_schedule_put_request_device_version import V1DevicesUpgradeSchedulePutRequestDeviceVersion

# TODO update the JSON string below
json = "{}"
# create an instance of V1DevicesUpgradeSchedulePutRequestDeviceVersion from a JSON string
v1_devices_upgrade_schedule_put_request_device_version_instance = V1DevicesUpgradeSchedulePutRequestDeviceVersion.from_json(json)
# print the JSON string representation of the object
print(V1DevicesUpgradeSchedulePutRequestDeviceVersion.to_json())

# convert the object into a dict
v1_devices_upgrade_schedule_put_request_device_version_dict = v1_devices_upgrade_schedule_put_request_device_version_instance.to_dict()
# create an instance of V1DevicesUpgradeSchedulePutRequestDeviceVersion from a dict
v1_devices_upgrade_schedule_put_request_device_version_from_dict = V1DevicesUpgradeSchedulePutRequestDeviceVersion.from_dict(v1_devices_upgrade_schedule_put_request_device_version_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


