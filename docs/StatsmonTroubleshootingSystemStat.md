# StatsmonTroubleshootingSystemStat


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**interface_name** | **str** |  | [optional] 
**peer_name** | **str** |  | [optional] 
**time** | [**GoogleProtobufTimestamp**](GoogleProtobufTimestamp.md) |  | [optional] 
**value** | **float** |  | [optional] 

## Example

```python
from graphiant_sdk.models.statsmon_troubleshooting_system_stat import StatsmonTroubleshootingSystemStat

# TODO update the JSON string below
json = "{}"
# create an instance of StatsmonTroubleshootingSystemStat from a JSON string
statsmon_troubleshooting_system_stat_instance = StatsmonTroubleshootingSystemStat.from_json(json)
# print the JSON string representation of the object
print(StatsmonTroubleshootingSystemStat.to_json())

# convert the object into a dict
statsmon_troubleshooting_system_stat_dict = statsmon_troubleshooting_system_stat_instance.to_dict()
# create an instance of StatsmonTroubleshootingSystemStat from a dict
statsmon_troubleshooting_system_stat_from_dict = StatsmonTroubleshootingSystemStat.from_dict(statsmon_troubleshooting_system_stat_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


