# DiagnosticToolsPrefixPort


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**port** | **int** | Filters the capture for the specified port | [optional] 
**prefix** | **str** | Filters the capture for the specified prefix | [optional] 

## Example

```python
from graphiant_sdk.models.diagnostic_tools_prefix_port import DiagnosticToolsPrefixPort

# TODO update the JSON string below
json = "{}"
# create an instance of DiagnosticToolsPrefixPort from a JSON string
diagnostic_tools_prefix_port_instance = DiagnosticToolsPrefixPort.from_json(json)
# print the JSON string representation of the object
print(DiagnosticToolsPrefixPort.to_json())

# convert the object into a dict
diagnostic_tools_prefix_port_dict = diagnostic_tools_prefix_port_instance.to_dict()
# create an instance of DiagnosticToolsPrefixPort from a dict
diagnostic_tools_prefix_port_from_dict = DiagnosticToolsPrefixPort.from_dict(diagnostic_tools_prefix_port_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


