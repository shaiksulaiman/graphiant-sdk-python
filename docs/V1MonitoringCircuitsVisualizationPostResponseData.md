# V1MonitoringCircuitsVisualizationPostResponseData


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**selector** | [**StatsmonTwampVisualSelector**](StatsmonTwampVisualSelector.md) |  | [optional] 
**twamp_visual_data** | [**List[StatsmonTwampVisualData]**](StatsmonTwampVisualData.md) |  | [optional] 

## Example

```python
from graphiant_sdk.models.v1_monitoring_circuits_visualization_post_response_data import V1MonitoringCircuitsVisualizationPostResponseData

# TODO update the JSON string below
json = "{}"
# create an instance of V1MonitoringCircuitsVisualizationPostResponseData from a JSON string
v1_monitoring_circuits_visualization_post_response_data_instance = V1MonitoringCircuitsVisualizationPostResponseData.from_json(json)
# print the JSON string representation of the object
print(V1MonitoringCircuitsVisualizationPostResponseData.to_json())

# convert the object into a dict
v1_monitoring_circuits_visualization_post_response_data_dict = v1_monitoring_circuits_visualization_post_response_data_instance.to_dict()
# create an instance of V1MonitoringCircuitsVisualizationPostResponseData from a dict
v1_monitoring_circuits_visualization_post_response_data_from_dict = V1MonitoringCircuitsVisualizationPostResponseData.from_dict(v1_monitoring_circuits_visualization_post_response_data_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


