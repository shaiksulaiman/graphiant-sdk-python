# StatsmonTroubleshootingDeviceFilter


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**device_id** | **int** |  | [optional] 
**device_name** | **str** |  | [optional] 

## Example

```python
from graphiant_sdk.models.statsmon_troubleshooting_device_filter import StatsmonTroubleshootingDeviceFilter

# TODO update the JSON string below
json = "{}"
# create an instance of StatsmonTroubleshootingDeviceFilter from a JSON string
statsmon_troubleshooting_device_filter_instance = StatsmonTroubleshootingDeviceFilter.from_json(json)
# print the JSON string representation of the object
print(StatsmonTroubleshootingDeviceFilter.to_json())

# convert the object into a dict
statsmon_troubleshooting_device_filter_dict = statsmon_troubleshooting_device_filter_instance.to_dict()
# create an instance of StatsmonTroubleshootingDeviceFilter from a dict
statsmon_troubleshooting_device_filter_from_dict = StatsmonTroubleshootingDeviceFilter.from_dict(statsmon_troubleshooting_device_filter_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


