# StatsmonV2SiteInfo


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**status** | **str** |  | [optional] 
**total_applications** | **int** |  | [optional] 
**total_circuits** | **int** |  | [optional] 
**total_edges** | **int** |  | [optional] 

## Example

```python
from graphiant_sdk.models.statsmon_v2_site_info import StatsmonV2SiteInfo

# TODO update the JSON string below
json = "{}"
# create an instance of StatsmonV2SiteInfo from a JSON string
statsmon_v2_site_info_instance = StatsmonV2SiteInfo.from_json(json)
# print the JSON string representation of the object
print(StatsmonV2SiteInfo.to_json())

# convert the object into a dict
statsmon_v2_site_info_dict = statsmon_v2_site_info_instance.to_dict()
# create an instance of StatsmonV2SiteInfo from a dict
statsmon_v2_site_info_from_dict = StatsmonV2SiteInfo.from_dict(statsmon_v2_site_info_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


