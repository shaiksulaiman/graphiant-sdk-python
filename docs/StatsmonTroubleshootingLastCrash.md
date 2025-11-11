# StatsmonTroubleshootingLastCrash


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**crash_details** | **str** |  | [optional] 
**reason** | **str** |  | [optional] 
**up_since_ts** | [**GoogleProtobufTimestamp**](GoogleProtobufTimestamp.md) |  | [optional] 

## Example

```python
from graphiant_sdk.models.statsmon_troubleshooting_last_crash import StatsmonTroubleshootingLastCrash

# TODO update the JSON string below
json = "{}"
# create an instance of StatsmonTroubleshootingLastCrash from a JSON string
statsmon_troubleshooting_last_crash_instance = StatsmonTroubleshootingLastCrash.from_json(json)
# print the JSON string representation of the object
print(StatsmonTroubleshootingLastCrash.to_json())

# convert the object into a dict
statsmon_troubleshooting_last_crash_dict = statsmon_troubleshooting_last_crash_instance.to_dict()
# create an instance of StatsmonTroubleshootingLastCrash from a dict
statsmon_troubleshooting_last_crash_from_dict = StatsmonTroubleshootingLastCrash.from_dict(statsmon_troubleshooting_last_crash_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


