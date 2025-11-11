# DiagnosticToolsPCapFilter


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**destination** | [**DiagnosticToolsPrefixPort**](DiagnosticToolsPrefixPort.md) |  | [optional] 
**dscp** | **int** | Filters the packet capture for the specified DSCP field | [optional] 
**protocol** | **str** | Filters the packet capture for the specified protocol | [optional] 
**source** | [**DiagnosticToolsPrefixPort**](DiagnosticToolsPrefixPort.md) |  | [optional] 

## Example

```python
from graphiant_sdk.models.diagnostic_tools_p_cap_filter import DiagnosticToolsPCapFilter

# TODO update the JSON string below
json = "{}"
# create an instance of DiagnosticToolsPCapFilter from a JSON string
diagnostic_tools_p_cap_filter_instance = DiagnosticToolsPCapFilter.from_json(json)
# print the JSON string representation of the object
print(DiagnosticToolsPCapFilter.to_json())

# convert the object into a dict
diagnostic_tools_p_cap_filter_dict = diagnostic_tools_p_cap_filter_instance.to_dict()
# create an instance of DiagnosticToolsPCapFilter from a dict
diagnostic_tools_p_cap_filter_from_dict = DiagnosticToolsPCapFilter.from_dict(diagnostic_tools_p_cap_filter_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


