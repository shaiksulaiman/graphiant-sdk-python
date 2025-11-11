# DiagnosticToolsPingResult


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**avg_loss** | **float** | % loss (required) | [optional] 
**avg_time** | **float** | Time in milli seconds (required) | [optional] 
**completed_time** | [**GoogleProtobufTimestamp**](GoogleProtobufTimestamp.md) |  | [optional] 
**max_time** | **float** | Time in milli seconds (required) | [optional] 
**min_time** | **float** | Time in milli seconds (required) | [optional] 
**result** | **str** | Success or Failed (required) | [optional] 

## Example

```python
from graphiant_sdk.models.diagnostic_tools_ping_result import DiagnosticToolsPingResult

# TODO update the JSON string below
json = "{}"
# create an instance of DiagnosticToolsPingResult from a JSON string
diagnostic_tools_ping_result_instance = DiagnosticToolsPingResult.from_json(json)
# print the JSON string representation of the object
print(DiagnosticToolsPingResult.to_json())

# convert the object into a dict
diagnostic_tools_ping_result_dict = diagnostic_tools_ping_result_instance.to_dict()
# create an instance of DiagnosticToolsPingResult from a dict
diagnostic_tools_ping_result_from_dict = DiagnosticToolsPingResult.from_dict(diagnostic_tools_ping_result_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


