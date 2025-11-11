# StatsmonTroubleshootingControlPlane


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**control_transitions** | [**List[StatsmonTroubleshootingTransitions]**](StatsmonTroubleshootingTransitions.md) |  | [optional] 
**management_transitions** | [**List[StatsmonTroubleshootingTransitions]**](StatsmonTroubleshootingTransitions.md) |  | [optional] 
**status** | **str** |  | [optional] 

## Example

```python
from graphiant_sdk.models.statsmon_troubleshooting_control_plane import StatsmonTroubleshootingControlPlane

# TODO update the JSON string below
json = "{}"
# create an instance of StatsmonTroubleshootingControlPlane from a JSON string
statsmon_troubleshooting_control_plane_instance = StatsmonTroubleshootingControlPlane.from_json(json)
# print the JSON string representation of the object
print(StatsmonTroubleshootingControlPlane.to_json())

# convert the object into a dict
statsmon_troubleshooting_control_plane_dict = statsmon_troubleshooting_control_plane_instance.to_dict()
# create an instance of StatsmonTroubleshootingControlPlane from a dict
statsmon_troubleshooting_control_plane_from_dict = StatsmonTroubleshootingControlPlane.from_dict(statsmon_troubleshooting_control_plane_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


