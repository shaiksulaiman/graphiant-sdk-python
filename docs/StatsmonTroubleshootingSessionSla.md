# StatsmonTroubleshootingSessionSla


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**name** | **str** |  | [optional] 
**values** | [**List[StatsmonTroubleshootingSlaValue]**](StatsmonTroubleshootingSlaValue.md) |  | [optional] 

## Example

```python
from graphiant_sdk.models.statsmon_troubleshooting_session_sla import StatsmonTroubleshootingSessionSla

# TODO update the JSON string below
json = "{}"
# create an instance of StatsmonTroubleshootingSessionSla from a JSON string
statsmon_troubleshooting_session_sla_instance = StatsmonTroubleshootingSessionSla.from_json(json)
# print the JSON string representation of the object
print(StatsmonTroubleshootingSessionSla.to_json())

# convert the object into a dict
statsmon_troubleshooting_session_sla_dict = statsmon_troubleshooting_session_sla_instance.to_dict()
# create an instance of StatsmonTroubleshootingSessionSla from a dict
statsmon_troubleshooting_session_sla_from_dict = StatsmonTroubleshootingSessionSla.from_dict(statsmon_troubleshooting_session_sla_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


