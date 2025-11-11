# StatsmonV2NodeDeviceInfo


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**control_quality** | **str** |  | [optional] 
**cpu** | **float** |  | [optional] 
**data_quality** | **str** |  | [optional] 
**device_id** | **int** |  | [optional] 
**hostname** | **str** |  | [optional] 
**location** | **str** |  | [optional] 
**maintenance_mode** | **bool** |  | [optional] 
**memory** | **float** |  | [optional] 
**mgmt_ip** | **str** |  | [optional] 
**model** | **str** |  | [optional] 
**portal_quality** | **str** |  | [optional] 
**serial_number** | **str** |  | [optional] 
**software_version** | **str** |  | [optional] 
**staging_mode** | **bool** |  | [optional] 
**temperature** | **float** |  | [optional] 
**uptime** | [**GoogleProtobufDuration**](GoogleProtobufDuration.md) |  | [optional] 

## Example

```python
from graphiant_sdk.models.statsmon_v2_node_device_info import StatsmonV2NodeDeviceInfo

# TODO update the JSON string below
json = "{}"
# create an instance of StatsmonV2NodeDeviceInfo from a JSON string
statsmon_v2_node_device_info_instance = StatsmonV2NodeDeviceInfo.from_json(json)
# print the JSON string representation of the object
print(StatsmonV2NodeDeviceInfo.to_json())

# convert the object into a dict
statsmon_v2_node_device_info_dict = statsmon_v2_node_device_info_instance.to_dict()
# create an instance of StatsmonV2NodeDeviceInfo from a dict
statsmon_v2_node_device_info_from_dict = StatsmonV2NodeDeviceInfo.from_dict(statsmon_v2_node_device_info_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


