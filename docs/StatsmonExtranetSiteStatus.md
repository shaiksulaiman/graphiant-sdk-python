# StatsmonExtranetSiteStatus


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**id** | **int** |  | [optional] 
**name** | **str** |  | [optional] 
**status** | **str** |  | [optional] 
**statuses** | [**List[StatsmonExtranetServerStatus]**](StatsmonExtranetServerStatus.md) |  | [optional] 

## Example

```python
from graphiant_sdk.models.statsmon_extranet_site_status import StatsmonExtranetSiteStatus

# TODO update the JSON string below
json = "{}"
# create an instance of StatsmonExtranetSiteStatus from a JSON string
statsmon_extranet_site_status_instance = StatsmonExtranetSiteStatus.from_json(json)
# print the JSON string representation of the object
print(StatsmonExtranetSiteStatus.to_json())

# convert the object into a dict
statsmon_extranet_site_status_dict = statsmon_extranet_site_status_instance.to_dict()
# create an instance of StatsmonExtranetSiteStatus from a dict
statsmon_extranet_site_status_from_dict = StatsmonExtranetSiteStatus.from_dict(statsmon_extranet_site_status_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


