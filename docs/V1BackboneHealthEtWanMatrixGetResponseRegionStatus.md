# V1BackboneHealthEtWanMatrixGetResponseRegionStatus


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**region** | [**StatsmonTroubleshootingRegion**](StatsmonTroubleshootingRegion.md) |  | [optional] 
**status** | **str** |  | [optional] 

## Example

```python
from graphiant_sdk.models.v1_backbone_health_et_wan_matrix_get_response_region_status import V1BackboneHealthEtWanMatrixGetResponseRegionStatus

# TODO update the JSON string below
json = "{}"
# create an instance of V1BackboneHealthEtWanMatrixGetResponseRegionStatus from a JSON string
v1_backbone_health_et_wan_matrix_get_response_region_status_instance = V1BackboneHealthEtWanMatrixGetResponseRegionStatus.from_json(json)
# print the JSON string representation of the object
print(V1BackboneHealthEtWanMatrixGetResponseRegionStatus.to_json())

# convert the object into a dict
v1_backbone_health_et_wan_matrix_get_response_region_status_dict = v1_backbone_health_et_wan_matrix_get_response_region_status_instance.to_dict()
# create an instance of V1BackboneHealthEtWanMatrixGetResponseRegionStatus from a dict
v1_backbone_health_et_wan_matrix_get_response_region_status_from_dict = V1BackboneHealthEtWanMatrixGetResponseRegionStatus.from_dict(v1_backbone_health_et_wan_matrix_get_response_region_status_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


