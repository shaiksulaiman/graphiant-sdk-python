# V2MonitoringCircuitsVisualizationPostResponse


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**data** | [**List[V2MonitoringCircuitsVisualizationPostResponseData]**](V2MonitoringCircuitsVisualizationPostResponseData.md) |  | [optional] 
**hostname** | **str** | hostname of the device. | [optional] 

## Example

```python
from graphiant_sdk.models.v2_monitoring_circuits_visualization_post_response import V2MonitoringCircuitsVisualizationPostResponse

# TODO update the JSON string below
json = "{}"
# create an instance of V2MonitoringCircuitsVisualizationPostResponse from a JSON string
v2_monitoring_circuits_visualization_post_response_instance = V2MonitoringCircuitsVisualizationPostResponse.from_json(json)
# print the JSON string representation of the object
print(V2MonitoringCircuitsVisualizationPostResponse.to_json())

# convert the object into a dict
v2_monitoring_circuits_visualization_post_response_dict = v2_monitoring_circuits_visualization_post_response_instance.to_dict()
# create an instance of V2MonitoringCircuitsVisualizationPostResponse from a dict
v2_monitoring_circuits_visualization_post_response_from_dict = V2MonitoringCircuitsVisualizationPostResponse.from_dict(v2_monitoring_circuits_visualization_post_response_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


