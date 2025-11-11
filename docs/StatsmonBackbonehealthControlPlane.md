# StatsmonBackbonehealthControlPlane


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**control_transitions** | [**StatsmonBackbonehealthTransitionSeries**](StatsmonBackbonehealthTransitionSeries.md) |  | [optional] 
**management_transitions** | [**StatsmonBackbonehealthTransitionSeries**](StatsmonBackbonehealthTransitionSeries.md) |  | [optional] 
**status** | **str** |  | [optional] 

## Example

```python
from graphiant_sdk.models.statsmon_backbonehealth_control_plane import StatsmonBackbonehealthControlPlane

# TODO update the JSON string below
json = "{}"
# create an instance of StatsmonBackbonehealthControlPlane from a JSON string
statsmon_backbonehealth_control_plane_instance = StatsmonBackbonehealthControlPlane.from_json(json)
# print the JSON string representation of the object
print(StatsmonBackbonehealthControlPlane.to_json())

# convert the object into a dict
statsmon_backbonehealth_control_plane_dict = statsmon_backbonehealth_control_plane_instance.to_dict()
# create an instance of StatsmonBackbonehealthControlPlane from a dict
statsmon_backbonehealth_control_plane_from_dict = StatsmonBackbonehealthControlPlane.from_dict(statsmon_backbonehealth_control_plane_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


