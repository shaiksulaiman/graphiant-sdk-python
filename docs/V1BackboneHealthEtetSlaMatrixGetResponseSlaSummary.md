# V1BackboneHealthEtetSlaMatrixGetResponseSlaSummary


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**delay_status** | **str** |  | [optional] 
**delay_value** | **float** |  | [optional] 
**device_id** | **int** |  | [optional] 
**device_name** | **str** |  | [optional] 
**jitter_status** | **str** |  | [optional] 
**jitter_value** | **float** |  | [optional] 
**loss_status** | **str** |  | [optional] 
**loss_value** | **float** |  | [optional] 
**mos_value** | **float** |  | [optional] 
**peer_device_id** | **int** |  | [optional] 
**peer_device_name** | **str** |  | [optional] 
**peer_region** | [**StatsmonTroubleshootingRegion**](StatsmonTroubleshootingRegion.md) |  | [optional] 
**region** | [**StatsmonTroubleshootingRegion**](StatsmonTroubleshootingRegion.md) |  | [optional] 
**status** | **str** |  | [optional] 

## Example

```python
from graphiant_sdk.models.v1_backbone_health_etet_sla_matrix_get_response_sla_summary import V1BackboneHealthEtetSlaMatrixGetResponseSlaSummary

# TODO update the JSON string below
json = "{}"
# create an instance of V1BackboneHealthEtetSlaMatrixGetResponseSlaSummary from a JSON string
v1_backbone_health_etet_sla_matrix_get_response_sla_summary_instance = V1BackboneHealthEtetSlaMatrixGetResponseSlaSummary.from_json(json)
# print the JSON string representation of the object
print(V1BackboneHealthEtetSlaMatrixGetResponseSlaSummary.to_json())

# convert the object into a dict
v1_backbone_health_etet_sla_matrix_get_response_sla_summary_dict = v1_backbone_health_etet_sla_matrix_get_response_sla_summary_instance.to_dict()
# create an instance of V1BackboneHealthEtetSlaMatrixGetResponseSlaSummary from a dict
v1_backbone_health_etet_sla_matrix_get_response_sla_summary_from_dict = V1BackboneHealthEtetSlaMatrixGetResponseSlaSummary.from_dict(v1_backbone_health_etet_sla_matrix_get_response_sla_summary_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


