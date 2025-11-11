# DiagnosticToolsDiagnosticResult


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**ping_result** | [**DiagnosticToolsPingResult**](DiagnosticToolsPingResult.md) |  | [optional] 
**route_info** | [**DiagnosticToolsRouteLookupResult**](DiagnosticToolsRouteLookupResult.md) |  | [optional] 
**trace_result** | [**DiagnosticToolsTracerouteResult**](DiagnosticToolsTracerouteResult.md) |  | [optional] 

## Example

```python
from graphiant_sdk.models.diagnostic_tools_diagnostic_result import DiagnosticToolsDiagnosticResult

# TODO update the JSON string below
json = "{}"
# create an instance of DiagnosticToolsDiagnosticResult from a JSON string
diagnostic_tools_diagnostic_result_instance = DiagnosticToolsDiagnosticResult.from_json(json)
# print the JSON string representation of the object
print(DiagnosticToolsDiagnosticResult.to_json())

# convert the object into a dict
diagnostic_tools_diagnostic_result_dict = diagnostic_tools_diagnostic_result_instance.to_dict()
# create an instance of DiagnosticToolsDiagnosticResult from a dict
diagnostic_tools_diagnostic_result_from_dict = DiagnosticToolsDiagnosticResult.from_dict(diagnostic_tools_diagnostic_result_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


