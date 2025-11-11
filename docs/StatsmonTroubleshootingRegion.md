# StatsmonTroubleshootingRegion


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**region_id** | **int** |  | [optional] 
**region_name** | **str** |  | [optional] 

## Example

```python
from graphiant_sdk.models.statsmon_troubleshooting_region import StatsmonTroubleshootingRegion

# TODO update the JSON string below
json = "{}"
# create an instance of StatsmonTroubleshootingRegion from a JSON string
statsmon_troubleshooting_region_instance = StatsmonTroubleshootingRegion.from_json(json)
# print the JSON string representation of the object
print(StatsmonTroubleshootingRegion.to_json())

# convert the object into a dict
statsmon_troubleshooting_region_dict = statsmon_troubleshooting_region_instance.to_dict()
# create an instance of StatsmonTroubleshootingRegion from a dict
statsmon_troubleshooting_region_from_dict = StatsmonTroubleshootingRegion.from_dict(statsmon_troubleshooting_region_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


