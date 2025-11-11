# StatsmonTroubleshootingSlaValue


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**delay_value** | **float** |  | [optional] 
**jitter_value** | **float** |  | [optional] 
**loss_value** | **float** |  | [optional] 
**status** | **str** |  | [optional] 
**time** | [**GoogleProtobufTimestamp**](GoogleProtobufTimestamp.md) |  | [optional] 
**value** | **float** |  | [optional] 

## Example

```python
from graphiant_sdk.models.statsmon_troubleshooting_sla_value import StatsmonTroubleshootingSlaValue

# TODO update the JSON string below
json = "{}"
# create an instance of StatsmonTroubleshootingSlaValue from a JSON string
statsmon_troubleshooting_sla_value_instance = StatsmonTroubleshootingSlaValue.from_json(json)
# print the JSON string representation of the object
print(StatsmonTroubleshootingSlaValue.to_json())

# convert the object into a dict
statsmon_troubleshooting_sla_value_dict = statsmon_troubleshooting_sla_value_instance.to_dict()
# create an instance of StatsmonTroubleshootingSlaValue from a dict
statsmon_troubleshooting_sla_value_from_dict = StatsmonTroubleshootingSlaValue.from_dict(statsmon_troubleshooting_sla_value_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


