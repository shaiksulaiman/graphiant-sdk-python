# StatsmonBackbonehealthSystemPlane


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**cpu** | [**List[StatsmonTroubleshootingSystemStat]**](StatsmonTroubleshootingSystemStat.md) |  | [optional] 
**crashes** | [**List[StatsmonTroubleshootingCrash]**](StatsmonTroubleshootingCrash.md) |  | [optional] 
**disk** | [**List[StatsmonTroubleshootingSystemStat]**](StatsmonTroubleshootingSystemStat.md) |  | [optional] 
**last_crash** | [**StatsmonTroubleshootingLastCrash**](StatsmonTroubleshootingLastCrash.md) |  | [optional] 
**maintenance_windows** | [**List[StatsmonTroubleshootingMaintenanceWindow]**](StatsmonTroubleshootingMaintenanceWindow.md) |  | [optional] 
**memory** | [**List[StatsmonTroubleshootingSystemStat]**](StatsmonTroubleshootingSystemStat.md) |  | [optional] 
**overheating** | [**List[StatsmonTroubleshootingOverheating]**](StatsmonTroubleshootingOverheating.md) |  | [optional] 
**status** | **str** |  | [optional] 
**temperature_series** | [**List[StatsmonTroubleshootingSystemStat]**](StatsmonTroubleshootingSystemStat.md) |  | [optional] 

## Example

```python
from graphiant_sdk.models.statsmon_backbonehealth_system_plane import StatsmonBackbonehealthSystemPlane

# TODO update the JSON string below
json = "{}"
# create an instance of StatsmonBackbonehealthSystemPlane from a JSON string
statsmon_backbonehealth_system_plane_instance = StatsmonBackbonehealthSystemPlane.from_json(json)
# print the JSON string representation of the object
print(StatsmonBackbonehealthSystemPlane.to_json())

# convert the object into a dict
statsmon_backbonehealth_system_plane_dict = statsmon_backbonehealth_system_plane_instance.to_dict()
# create an instance of StatsmonBackbonehealthSystemPlane from a dict
statsmon_backbonehealth_system_plane_from_dict = StatsmonBackbonehealthSystemPlane.from_dict(statsmon_backbonehealth_system_plane_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


