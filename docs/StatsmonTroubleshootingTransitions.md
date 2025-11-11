# StatsmonTroubleshootingTransitions


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**name** | **str** |  | [optional] 
**transitions** | [**List[StatsmonTroubleshootingSystemStat]**](StatsmonTroubleshootingSystemStat.md) |  | [optional] 

## Example

```python
from graphiant_sdk.models.statsmon_troubleshooting_transitions import StatsmonTroubleshootingTransitions

# TODO update the JSON string below
json = "{}"
# create an instance of StatsmonTroubleshootingTransitions from a JSON string
statsmon_troubleshooting_transitions_instance = StatsmonTroubleshootingTransitions.from_json(json)
# print the JSON string representation of the object
print(StatsmonTroubleshootingTransitions.to_json())

# convert the object into a dict
statsmon_troubleshooting_transitions_dict = statsmon_troubleshooting_transitions_instance.to_dict()
# create an instance of StatsmonTroubleshootingTransitions from a dict
statsmon_troubleshooting_transitions_from_dict = StatsmonTroubleshootingTransitions.from_dict(statsmon_troubleshooting_transitions_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


