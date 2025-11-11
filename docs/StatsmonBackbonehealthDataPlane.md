# StatsmonBackbonehealthDataPlane


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**down_transitions** | [**List[StatsmonBackbonehealthTransitions]**](StatsmonBackbonehealthTransitions.md) |  | [optional] 
**session_slas** | [**List[StatsmonTroubleshootingSessionSla]**](StatsmonTroubleshootingSessionSla.md) |  | [optional] 
**status** | **str** |  | [optional] 

## Example

```python
from graphiant_sdk.models.statsmon_backbonehealth_data_plane import StatsmonBackbonehealthDataPlane

# TODO update the JSON string below
json = "{}"
# create an instance of StatsmonBackbonehealthDataPlane from a JSON string
statsmon_backbonehealth_data_plane_instance = StatsmonBackbonehealthDataPlane.from_json(json)
# print the JSON string representation of the object
print(StatsmonBackbonehealthDataPlane.to_json())

# convert the object into a dict
statsmon_backbonehealth_data_plane_dict = statsmon_backbonehealth_data_plane_instance.to_dict()
# create an instance of StatsmonBackbonehealthDataPlane from a dict
statsmon_backbonehealth_data_plane_from_dict = StatsmonBackbonehealthDataPlane.from_dict(statsmon_backbonehealth_data_plane_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


