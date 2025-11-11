# V1BackboneHealthEtWanMatrixGetResponse


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**device_etwan_summary** | [**List[V1BackboneHealthEtWanMatrixGetResponseDeviceEtWanSummary]**](V1BackboneHealthEtWanMatrixGetResponseDeviceEtWanSummary.md) |  | [optional] 
**region_sla_status** | [**List[V1BackboneHealthEtWanMatrixGetResponseRegionStatus]**](V1BackboneHealthEtWanMatrixGetResponseRegionStatus.md) |  | [optional] 

## Example

```python
from graphiant_sdk.models.v1_backbone_health_et_wan_matrix_get_response import V1BackboneHealthEtWanMatrixGetResponse

# TODO update the JSON string below
json = "{}"
# create an instance of V1BackboneHealthEtWanMatrixGetResponse from a JSON string
v1_backbone_health_et_wan_matrix_get_response_instance = V1BackboneHealthEtWanMatrixGetResponse.from_json(json)
# print the JSON string representation of the object
print(V1BackboneHealthEtWanMatrixGetResponse.to_json())

# convert the object into a dict
v1_backbone_health_et_wan_matrix_get_response_dict = v1_backbone_health_et_wan_matrix_get_response_instance.to_dict()
# create an instance of V1BackboneHealthEtWanMatrixGetResponse from a dict
v1_backbone_health_et_wan_matrix_get_response_from_dict = V1BackboneHealthEtWanMatrixGetResponse.from_dict(v1_backbone_health_et_wan_matrix_get_response_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


