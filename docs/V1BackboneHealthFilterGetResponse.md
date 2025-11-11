# V1BackboneHealthFilterGetResponse


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**circuits** | [**List[StatsmonTroubleshootingCircuitFilter]**](StatsmonTroubleshootingCircuitFilter.md) |  | [optional] 
**devices** | [**List[StatsmonTroubleshootingDeviceFilter]**](StatsmonTroubleshootingDeviceFilter.md) |  | [optional] 
**lan_segments** | [**List[StatsmonTroubleshootingLanSegmentFilter]**](StatsmonTroubleshootingLanSegmentFilter.md) |  | [optional] 
**regions** | [**List[StatsmonTroubleshootingRegionFilter]**](StatsmonTroubleshootingRegionFilter.md) |  | [optional] 
**sites** | [**List[StatsmonTroubleshootingSiteFilter]**](StatsmonTroubleshootingSiteFilter.md) |  | [optional] 

## Example

```python
from graphiant_sdk.models.v1_backbone_health_filter_get_response import V1BackboneHealthFilterGetResponse

# TODO update the JSON string below
json = "{}"
# create an instance of V1BackboneHealthFilterGetResponse from a JSON string
v1_backbone_health_filter_get_response_instance = V1BackboneHealthFilterGetResponse.from_json(json)
# print the JSON string representation of the object
print(V1BackboneHealthFilterGetResponse.to_json())

# convert the object into a dict
v1_backbone_health_filter_get_response_dict = v1_backbone_health_filter_get_response_instance.to_dict()
# create an instance of V1BackboneHealthFilterGetResponse from a dict
v1_backbone_health_filter_get_response_from_dict = V1BackboneHealthFilterGetResponse.from_dict(v1_backbone_health_filter_get_response_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


