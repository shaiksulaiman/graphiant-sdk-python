# V1BackboneHealthOverviewPostResponseDeviceSummary


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**control_status** | **str** |  | [optional] 
**data_status** | **str** |  | [optional] 
**device_id** | **int** |  | [optional] 
**device_name** | **str** |  | [optional] 
**device_role** | **str** |  | [optional] 
**overall_status** | **str** |  | [optional] 
**region** | [**StatsmonTroubleshootingRegion**](StatsmonTroubleshootingRegion.md) |  | [optional] 
**selected_status** | **str** |  | [optional] 
**system_status** | **str** |  | [optional] 

## Example

```python
from graphiant_sdk.models.v1_backbone_health_overview_post_response_device_summary import V1BackboneHealthOverviewPostResponseDeviceSummary

# TODO update the JSON string below
json = "{}"
# create an instance of V1BackboneHealthOverviewPostResponseDeviceSummary from a JSON string
v1_backbone_health_overview_post_response_device_summary_instance = V1BackboneHealthOverviewPostResponseDeviceSummary.from_json(json)
# print the JSON string representation of the object
print(V1BackboneHealthOverviewPostResponseDeviceSummary.to_json())

# convert the object into a dict
v1_backbone_health_overview_post_response_device_summary_dict = v1_backbone_health_overview_post_response_device_summary_instance.to_dict()
# create an instance of V1BackboneHealthOverviewPostResponseDeviceSummary from a dict
v1_backbone_health_overview_post_response_device_summary_from_dict = V1BackboneHealthOverviewPostResponseDeviceSummary.from_dict(v1_backbone_health_overview_post_response_device_summary_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


