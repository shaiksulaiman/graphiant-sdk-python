# StatsmonBackbonehealthTransitions


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**name** | **str** |  | [optional] 
**transitions** | [**List[StatsmonTroubleshootingSystemStat]**](StatsmonTroubleshootingSystemStat.md) |  | [optional] 

## Example

```python
from graphiant_sdk.models.statsmon_backbonehealth_transitions import StatsmonBackbonehealthTransitions

# TODO update the JSON string below
json = "{}"
# create an instance of StatsmonBackbonehealthTransitions from a JSON string
statsmon_backbonehealth_transitions_instance = StatsmonBackbonehealthTransitions.from_json(json)
# print the JSON string representation of the object
print(StatsmonBackbonehealthTransitions.to_json())

# convert the object into a dict
statsmon_backbonehealth_transitions_dict = statsmon_backbonehealth_transitions_instance.to_dict()
# create an instance of StatsmonBackbonehealthTransitions from a dict
statsmon_backbonehealth_transitions_from_dict = StatsmonBackbonehealthTransitions.from_dict(statsmon_backbonehealth_transitions_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


