# V1AppsVisualizationPostResponse


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**app_health** | **Dict[str, int]** |  | [optional] 
**apps_on_device_count** | **int** |  | [optional] 
**apps_visualization** | [**List[IpfixAppVisualization]**](IpfixAppVisualization.md) |  | [optional] 
**average_qoe** | **float** |  | [optional] 

## Example

```python
from graphiant_sdk.models.v1_apps_visualization_post_response import V1AppsVisualizationPostResponse

# TODO update the JSON string below
json = "{}"
# create an instance of V1AppsVisualizationPostResponse from a JSON string
v1_apps_visualization_post_response_instance = V1AppsVisualizationPostResponse.from_json(json)
# print the JSON string representation of the object
print(V1AppsVisualizationPostResponse.to_json())

# convert the object into a dict
v1_apps_visualization_post_response_dict = v1_apps_visualization_post_response_instance.to_dict()
# create an instance of V1AppsVisualizationPostResponse from a dict
v1_apps_visualization_post_response_from_dict = V1AppsVisualizationPostResponse.from_dict(v1_apps_visualization_post_response_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


