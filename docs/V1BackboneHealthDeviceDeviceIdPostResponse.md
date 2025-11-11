# V1BackboneHealthDeviceDeviceIdPostResponse


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**control_plane** | [**StatsmonBackbonehealthControlPlane**](StatsmonBackbonehealthControlPlane.md) |  | [optional] 
**data_plane** | [**StatsmonBackbonehealthDataPlane**](StatsmonBackbonehealthDataPlane.md) |  | [optional] 
**issues** | [**List[StatsmonTroubleshootingIssue]**](StatsmonTroubleshootingIssue.md) |  | [optional] 
**qoe_matrix** | [**StatsmonBackbonehealthGetQoeMatrixResponse**](StatsmonBackbonehealthGetQoeMatrixResponse.md) |  | [optional] 
**role** | **str** |  | [optional] 
**status** | **str** |  | [optional] 
**sw_version** | **str** |  | [optional] 
**sw_version_v2** | [**UpgradeSwVersion**](UpgradeSwVersion.md) |  | [optional] 
**system_plane** | [**StatsmonBackbonehealthSystemPlane**](StatsmonBackbonehealthSystemPlane.md) |  | [optional] 
**up_since_ts** | [**GoogleProtobufTimestamp**](GoogleProtobufTimestamp.md) |  | [optional] 

## Example

```python
from graphiant_sdk.models.v1_backbone_health_device_device_id_post_response import V1BackboneHealthDeviceDeviceIdPostResponse

# TODO update the JSON string below
json = "{}"
# create an instance of V1BackboneHealthDeviceDeviceIdPostResponse from a JSON string
v1_backbone_health_device_device_id_post_response_instance = V1BackboneHealthDeviceDeviceIdPostResponse.from_json(json)
# print the JSON string representation of the object
print(V1BackboneHealthDeviceDeviceIdPostResponse.to_json())

# convert the object into a dict
v1_backbone_health_device_device_id_post_response_dict = v1_backbone_health_device_device_id_post_response_instance.to_dict()
# create an instance of V1BackboneHealthDeviceDeviceIdPostResponse from a dict
v1_backbone_health_device_device_id_post_response_from_dict = V1BackboneHealthDeviceDeviceIdPostResponse.from_dict(v1_backbone_health_device_device_id_post_response_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


