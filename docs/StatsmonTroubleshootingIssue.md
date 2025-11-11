# StatsmonTroubleshootingIssue


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**alert_id** | **str** |  | [optional] 
**allow_listed** | **bool** |  | [optional] 
**component** | **str** |  | [optional] 
**end_time** | [**GoogleProtobufTimestamp**](GoogleProtobufTimestamp.md) |  | [optional] 
**entity** | **str** |  | [optional] 
**issue** | **str** |  | [optional] 
**mute_listed** | **bool** |  | [optional] 
**notification_created** | **bool** |  | [optional] 
**plane** | **str** |  | [optional] 
**reason** | **str** |  | [optional] 
**severity** | **str** |  | [optional] 
**start_time** | [**GoogleProtobufTimestamp**](GoogleProtobufTimestamp.md) |  | [optional] 
**status** | **str** |  | [optional] 

## Example

```python
from graphiant_sdk.models.statsmon_troubleshooting_issue import StatsmonTroubleshootingIssue

# TODO update the JSON string below
json = "{}"
# create an instance of StatsmonTroubleshootingIssue from a JSON string
statsmon_troubleshooting_issue_instance = StatsmonTroubleshootingIssue.from_json(json)
# print the JSON string representation of the object
print(StatsmonTroubleshootingIssue.to_json())

# convert the object into a dict
statsmon_troubleshooting_issue_dict = statsmon_troubleshooting_issue_instance.to_dict()
# create an instance of StatsmonTroubleshootingIssue from a dict
statsmon_troubleshooting_issue_from_dict = StatsmonTroubleshootingIssue.from_dict(statsmon_troubleshooting_issue_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


