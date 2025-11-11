# IpfixAppVisualization


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**app_id** | **int** |  | [optional] 
**app_name** | **str** |  | [optional] 
**circuit_availability** | **Dict[str, int]** |  | [optional] 
**circuit_map** | [**Dict[str, IpfixCircuitMetrics]**](IpfixCircuitMetrics.md) |  | [optional] 
**current_status** | **str** | current status of the app. | [optional] 

## Example

```python
from graphiant_sdk.models.ipfix_app_visualization import IpfixAppVisualization

# TODO update the JSON string below
json = "{}"
# create an instance of IpfixAppVisualization from a JSON string
ipfix_app_visualization_instance = IpfixAppVisualization.from_json(json)
# print the JSON string representation of the object
print(IpfixAppVisualization.to_json())

# convert the object into a dict
ipfix_app_visualization_dict = ipfix_app_visualization_instance.to_dict()
# create an instance of IpfixAppVisualization from a dict
ipfix_app_visualization_from_dict = IpfixAppVisualization.from_dict(ipfix_app_visualization_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


