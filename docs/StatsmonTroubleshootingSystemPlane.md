# StatsmonTroubleshootingSystemPlane


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**cpu** | [**List[StatsmonTroubleshootingSystemStat]**](StatsmonTroubleshootingSystemStat.md) |  | [optional] 
**crashes** | [**List[StatsmonTroubleshootingCrash]**](StatsmonTroubleshootingCrash.md) |  | [optional] 
**disk** | [**List[StatsmonTroubleshootingSystemStat]**](StatsmonTroubleshootingSystemStat.md) |  | [optional] 
**last_crash** | [**StatsmonTroubleshootingLastCrash**](StatsmonTroubleshootingLastCrash.md) |  | [optional] 
**maintenance_windows** | [**List[StatsmonTroubleshootingMaintenanceWindow]**](StatsmonTroubleshootingMaintenanceWindow.md) |  | [optional] 
**memory** | [**List[StatsmonTroubleshootingSystemStat]**](StatsmonTroubleshootingSystemStat.md) |  | [optional] 
**status** | **str** |  | [optional] 
**temperature** | [**List[StatsmonTroubleshootingOverheating]**](StatsmonTroubleshootingOverheating.md) |  | [optional] 
**temperature_series** | [**List[StatsmonTroubleshootingSystemStat]**](StatsmonTroubleshootingSystemStat.md) |  | [optional] 

## Example

```python
from graphiant_sdk.models.statsmon_troubleshooting_system_plane import StatsmonTroubleshootingSystemPlane

# TODO update the JSON string below
json = "{}"
# create an instance of StatsmonTroubleshootingSystemPlane from a JSON string
statsmon_troubleshooting_system_plane_instance = StatsmonTroubleshootingSystemPlane.from_json(json)
# print the JSON string representation of the object
print(StatsmonTroubleshootingSystemPlane.to_json())

# convert the object into a dict
statsmon_troubleshooting_system_plane_dict = statsmon_troubleshooting_system_plane_instance.to_dict()
# create an instance of StatsmonTroubleshootingSystemPlane from a dict
statsmon_troubleshooting_system_plane_from_dict = StatsmonTroubleshootingSystemPlane.from_dict(statsmon_troubleshooting_system_plane_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


