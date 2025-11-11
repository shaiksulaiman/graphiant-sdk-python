# V1TroubleshootingDeviceDeviceIdPostResponse


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**maintenance_mode** | **bool** |  | [optional] 
**colr_active** | **bool** |  | [optional] 
**control_plane** | [**StatsmonTroubleshootingControlPlane**](StatsmonTroubleshootingControlPlane.md) |  | [optional] 
**data_plane** | [**StatsmonTroubleshootingDataPlane**](StatsmonTroubleshootingDataPlane.md) |  | [optional] 
**issues** | [**List[StatsmonTroubleshootingIssue]**](StatsmonTroubleshootingIssue.md) |  | [optional] 
**lifecycle_status** | **str** |  | [optional] 
**status** | **str** |  | [optional] 
**sw_version** | **str** |  | [optional] 
**sw_version_v2** | [**UpgradeSwVersion**](UpgradeSwVersion.md) |  | [optional] 
**system_plane** | [**StatsmonTroubleshootingSystemPlane**](StatsmonTroubleshootingSystemPlane.md) |  | [optional] 
**up_since_ts** | [**GoogleProtobufTimestamp**](GoogleProtobufTimestamp.md) |  | [optional] 

## Example

```python
from graphiant_sdk.models.v1_troubleshooting_device_device_id_post_response import V1TroubleshootingDeviceDeviceIdPostResponse

# TODO update the JSON string below
json = "{}"
# create an instance of V1TroubleshootingDeviceDeviceIdPostResponse from a JSON string
v1_troubleshooting_device_device_id_post_response_instance = V1TroubleshootingDeviceDeviceIdPostResponse.from_json(json)
# print the JSON string representation of the object
print(V1TroubleshootingDeviceDeviceIdPostResponse.to_json())

# convert the object into a dict
v1_troubleshooting_device_device_id_post_response_dict = v1_troubleshooting_device_device_id_post_response_instance.to_dict()
# create an instance of V1TroubleshootingDeviceDeviceIdPostResponse from a dict
v1_troubleshooting_device_device_id_post_response_from_dict = V1TroubleshootingDeviceDeviceIdPostResponse.from_dict(v1_troubleshooting_device_device_id_post_response_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


