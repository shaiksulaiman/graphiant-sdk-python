# StatsmonTroubleshootingSiteFilter


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**site_id** | **int** |  | [optional] 
**site_name** | **str** |  | [optional] 

## Example

```python
from graphiant_sdk.models.statsmon_troubleshooting_site_filter import StatsmonTroubleshootingSiteFilter

# TODO update the JSON string below
json = "{}"
# create an instance of StatsmonTroubleshootingSiteFilter from a JSON string
statsmon_troubleshooting_site_filter_instance = StatsmonTroubleshootingSiteFilter.from_json(json)
# print the JSON string representation of the object
print(StatsmonTroubleshootingSiteFilter.to_json())

# convert the object into a dict
statsmon_troubleshooting_site_filter_dict = statsmon_troubleshooting_site_filter_instance.to_dict()
# create an instance of StatsmonTroubleshootingSiteFilter from a dict
statsmon_troubleshooting_site_filter_from_dict = StatsmonTroubleshootingSiteFilter.from_dict(statsmon_troubleshooting_site_filter_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


