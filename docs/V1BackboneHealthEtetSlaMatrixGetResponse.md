# V1BackboneHealthEtetSlaMatrixGetResponse


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**devices** | [**List[V1BackboneHealthEtetSlaMatrixGetResponseDevicesSummary]**](V1BackboneHealthEtetSlaMatrixGetResponseDevicesSummary.md) |  | [optional] 
**region_status** | [**List[V1BackboneHealthEtetSlaMatrixGetResponseRegionStatus]**](V1BackboneHealthEtetSlaMatrixGetResponseRegionStatus.md) |  | [optional] 
**sla_matrix** | [**List[V1BackboneHealthEtetSlaMatrixGetResponseSlaSummary]**](V1BackboneHealthEtetSlaMatrixGetResponseSlaSummary.md) |  | [optional] 

## Example

```python
from graphiant_sdk.models.v1_backbone_health_etet_sla_matrix_get_response import V1BackboneHealthEtetSlaMatrixGetResponse

# TODO update the JSON string below
json = "{}"
# create an instance of V1BackboneHealthEtetSlaMatrixGetResponse from a JSON string
v1_backbone_health_etet_sla_matrix_get_response_instance = V1BackboneHealthEtetSlaMatrixGetResponse.from_json(json)
# print the JSON string representation of the object
print(V1BackboneHealthEtetSlaMatrixGetResponse.to_json())

# convert the object into a dict
v1_backbone_health_etet_sla_matrix_get_response_dict = v1_backbone_health_etet_sla_matrix_get_response_instance.to_dict()
# create an instance of V1BackboneHealthEtetSlaMatrixGetResponse from a dict
v1_backbone_health_etet_sla_matrix_get_response_from_dict = V1BackboneHealthEtetSlaMatrixGetResponse.from_dict(v1_backbone_health_etet_sla_matrix_get_response_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


