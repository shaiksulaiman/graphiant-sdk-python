# V1MonitoringCircuitsVisualizationPostResponse


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**data** | [**List[V1MonitoringCircuitsVisualizationPostResponseData]**](V1MonitoringCircuitsVisualizationPostResponseData.md) |  | [optional] 
**hostname** | **str** | hostname of the device. | [optional] 

## Example

```python
from graphiant_sdk.models.v1_monitoring_circuits_visualization_post_response import V1MonitoringCircuitsVisualizationPostResponse

# TODO update the JSON string below
json = "{}"
# create an instance of V1MonitoringCircuitsVisualizationPostResponse from a JSON string
v1_monitoring_circuits_visualization_post_response_instance = V1MonitoringCircuitsVisualizationPostResponse.from_json(json)
# print the JSON string representation of the object
print(V1MonitoringCircuitsVisualizationPostResponse.to_json())

# convert the object into a dict
v1_monitoring_circuits_visualization_post_response_dict = v1_monitoring_circuits_visualization_post_response_instance.to_dict()
# create an instance of V1MonitoringCircuitsVisualizationPostResponse from a dict
v1_monitoring_circuits_visualization_post_response_from_dict = V1MonitoringCircuitsVisualizationPostResponse.from_dict(v1_monitoring_circuits_visualization_post_response_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


