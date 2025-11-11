# V1BackboneHealthOverviewPostResponse


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**devices** | [**List[V1BackboneHealthOverviewPostResponseDeviceSummary]**](V1BackboneHealthOverviewPostResponseDeviceSummary.md) |  | [optional] 

## Example

```python
from graphiant_sdk.models.v1_backbone_health_overview_post_response import V1BackboneHealthOverviewPostResponse

# TODO update the JSON string below
json = "{}"
# create an instance of V1BackboneHealthOverviewPostResponse from a JSON string
v1_backbone_health_overview_post_response_instance = V1BackboneHealthOverviewPostResponse.from_json(json)
# print the JSON string representation of the object
print(V1BackboneHealthOverviewPostResponse.to_json())

# convert the object into a dict
v1_backbone_health_overview_post_response_dict = v1_backbone_health_overview_post_response_instance.to_dict()
# create an instance of V1BackboneHealthOverviewPostResponse from a dict
v1_backbone_health_overview_post_response_from_dict = V1BackboneHealthOverviewPostResponse.from_dict(v1_backbone_health_overview_post_response_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


