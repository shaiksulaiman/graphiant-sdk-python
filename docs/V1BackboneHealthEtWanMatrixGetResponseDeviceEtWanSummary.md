# V1BackboneHealthEtWanMatrixGetResponseDeviceEtWanSummary


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**device_id** | **int** |  | [optional] 
**device_name** | **str** |  | [optional] 
**provider** | **str** |  | [optional] 
**region** | [**StatsmonTroubleshootingRegion**](StatsmonTroubleshootingRegion.md) |  | [optional] 
**status** | **str** |  | [optional] 

## Example

```python
from graphiant_sdk.models.v1_backbone_health_et_wan_matrix_get_response_device_et_wan_summary import V1BackboneHealthEtWanMatrixGetResponseDeviceEtWanSummary

# TODO update the JSON string below
json = "{}"
# create an instance of V1BackboneHealthEtWanMatrixGetResponseDeviceEtWanSummary from a JSON string
v1_backbone_health_et_wan_matrix_get_response_device_et_wan_summary_instance = V1BackboneHealthEtWanMatrixGetResponseDeviceEtWanSummary.from_json(json)
# print the JSON string representation of the object
print(V1BackboneHealthEtWanMatrixGetResponseDeviceEtWanSummary.to_json())

# convert the object into a dict
v1_backbone_health_et_wan_matrix_get_response_device_et_wan_summary_dict = v1_backbone_health_et_wan_matrix_get_response_device_et_wan_summary_instance.to_dict()
# create an instance of V1BackboneHealthEtWanMatrixGetResponseDeviceEtWanSummary from a dict
v1_backbone_health_et_wan_matrix_get_response_device_et_wan_summary_from_dict = V1BackboneHealthEtWanMatrixGetResponseDeviceEtWanSummary.from_dict(v1_backbone_health_et_wan_matrix_get_response_device_et_wan_summary_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


