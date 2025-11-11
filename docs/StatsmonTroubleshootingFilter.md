# StatsmonTroubleshootingFilter


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**circuit_names** | **List[str]** |  | [optional] 
**device_ids** | **List[int]** |  | [optional] 
**lan_segments** | **List[str]** |  | [optional] 
**region_ids** | **List[int]** |  | [optional] 
**site_ids** | **List[int]** |  | [optional] 

## Example

```python
from graphiant_sdk.models.statsmon_troubleshooting_filter import StatsmonTroubleshootingFilter

# TODO update the JSON string below
json = "{}"
# create an instance of StatsmonTroubleshootingFilter from a JSON string
statsmon_troubleshooting_filter_instance = StatsmonTroubleshootingFilter.from_json(json)
# print the JSON string representation of the object
print(StatsmonTroubleshootingFilter.to_json())

# convert the object into a dict
statsmon_troubleshooting_filter_dict = statsmon_troubleshooting_filter_instance.to_dict()
# create an instance of StatsmonTroubleshootingFilter from a dict
statsmon_troubleshooting_filter_from_dict = StatsmonTroubleshootingFilter.from_dict(statsmon_troubleshooting_filter_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


