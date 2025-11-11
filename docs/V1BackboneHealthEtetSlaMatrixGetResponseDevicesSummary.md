# V1BackboneHealthEtetSlaMatrixGetResponseDevicesSummary


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**device_id** | **int** |  | [optional] 
**device_name** | **str** |  | [optional] 
**region** | [**StatsmonTroubleshootingRegion**](StatsmonTroubleshootingRegion.md) |  | [optional] 

## Example

```python
from graphiant_sdk.models.v1_backbone_health_etet_sla_matrix_get_response_devices_summary import V1BackboneHealthEtetSlaMatrixGetResponseDevicesSummary

# TODO update the JSON string below
json = "{}"
# create an instance of V1BackboneHealthEtetSlaMatrixGetResponseDevicesSummary from a JSON string
v1_backbone_health_etet_sla_matrix_get_response_devices_summary_instance = V1BackboneHealthEtetSlaMatrixGetResponseDevicesSummary.from_json(json)
# print the JSON string representation of the object
print(V1BackboneHealthEtetSlaMatrixGetResponseDevicesSummary.to_json())

# convert the object into a dict
v1_backbone_health_etet_sla_matrix_get_response_devices_summary_dict = v1_backbone_health_etet_sla_matrix_get_response_devices_summary_instance.to_dict()
# create an instance of V1BackboneHealthEtetSlaMatrixGetResponseDevicesSummary from a dict
v1_backbone_health_etet_sla_matrix_get_response_devices_summary_from_dict = V1BackboneHealthEtetSlaMatrixGetResponseDevicesSummary.from_dict(v1_backbone_health_etet_sla_matrix_get_response_devices_summary_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


