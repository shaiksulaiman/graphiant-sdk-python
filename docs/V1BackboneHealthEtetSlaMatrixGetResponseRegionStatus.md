# V1BackboneHealthEtetSlaMatrixGetResponseRegionStatus


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**peer_region** | [**StatsmonTroubleshootingRegion**](StatsmonTroubleshootingRegion.md) |  | [optional] 
**region** | [**StatsmonTroubleshootingRegion**](StatsmonTroubleshootingRegion.md) |  | [optional] 
**status** | **str** |  | [optional] 

## Example

```python
from graphiant_sdk.models.v1_backbone_health_etet_sla_matrix_get_response_region_status import V1BackboneHealthEtetSlaMatrixGetResponseRegionStatus

# TODO update the JSON string below
json = "{}"
# create an instance of V1BackboneHealthEtetSlaMatrixGetResponseRegionStatus from a JSON string
v1_backbone_health_etet_sla_matrix_get_response_region_status_instance = V1BackboneHealthEtetSlaMatrixGetResponseRegionStatus.from_json(json)
# print the JSON string representation of the object
print(V1BackboneHealthEtetSlaMatrixGetResponseRegionStatus.to_json())

# convert the object into a dict
v1_backbone_health_etet_sla_matrix_get_response_region_status_dict = v1_backbone_health_etet_sla_matrix_get_response_region_status_instance.to_dict()
# create an instance of V1BackboneHealthEtetSlaMatrixGetResponseRegionStatus from a dict
v1_backbone_health_etet_sla_matrix_get_response_region_status_from_dict = V1BackboneHealthEtetSlaMatrixGetResponseRegionStatus.from_dict(v1_backbone_health_etet_sla_matrix_get_response_region_status_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


