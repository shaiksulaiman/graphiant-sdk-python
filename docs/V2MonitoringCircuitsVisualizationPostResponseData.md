# V2MonitoringCircuitsVisualizationPostResponseData


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**samples** | [**List[StatsmonV2StatsSample]**](StatsmonV2StatsSample.md) |  | [optional] 
**selector** | [**StatsmonV2TwampVisualSelector**](StatsmonV2TwampVisualSelector.md) |  | [optional] 

## Example

```python
from graphiant_sdk.models.v2_monitoring_circuits_visualization_post_response_data import V2MonitoringCircuitsVisualizationPostResponseData

# TODO update the JSON string below
json = "{}"
# create an instance of V2MonitoringCircuitsVisualizationPostResponseData from a JSON string
v2_monitoring_circuits_visualization_post_response_data_instance = V2MonitoringCircuitsVisualizationPostResponseData.from_json(json)
# print the JSON string representation of the object
print(V2MonitoringCircuitsVisualizationPostResponseData.to_json())

# convert the object into a dict
v2_monitoring_circuits_visualization_post_response_data_dict = v2_monitoring_circuits_visualization_post_response_data_instance.to_dict()
# create an instance of V2MonitoringCircuitsVisualizationPostResponseData from a dict
v2_monitoring_circuits_visualization_post_response_data_from_dict = V2MonitoringCircuitsVisualizationPostResponseData.from_dict(v2_monitoring_circuits_visualization_post_response_data_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


