# StatsmonTroubleshootingEdgeStatus


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**device_id** | **int** |  | [optional] 
**device_name** | **str** |  | [optional] 
**device_status** | **str** |  | [optional] 

## Example

```python
from graphiant_sdk.models.statsmon_troubleshooting_edge_status import StatsmonTroubleshootingEdgeStatus

# TODO update the JSON string below
json = "{}"
# create an instance of StatsmonTroubleshootingEdgeStatus from a JSON string
statsmon_troubleshooting_edge_status_instance = StatsmonTroubleshootingEdgeStatus.from_json(json)
# print the JSON string representation of the object
print(StatsmonTroubleshootingEdgeStatus.to_json())

# convert the object into a dict
statsmon_troubleshooting_edge_status_dict = statsmon_troubleshooting_edge_status_instance.to_dict()
# create an instance of StatsmonTroubleshootingEdgeStatus from a dict
statsmon_troubleshooting_edge_status_from_dict = StatsmonTroubleshootingEdgeStatus.from_dict(statsmon_troubleshooting_edge_status_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


