# DiagnosticToolsSpeedtestParams


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**provider** | **str** | Speedtest provider name (required) | 
**server_id** | **str** | This is fetched using GetSpeedtestServers API | [optional] 
**target** | [**DiagnosticToolsTargetType**](DiagnosticToolsTargetType.md) |  | 
**token** | **str** | Token to be sent in subsequent lookup | [optional] 

## Example

```python
from graphiant_sdk.models.diagnostic_tools_speedtest_params import DiagnosticToolsSpeedtestParams

# TODO update the JSON string below
json = "{}"
# create an instance of DiagnosticToolsSpeedtestParams from a JSON string
diagnostic_tools_speedtest_params_instance = DiagnosticToolsSpeedtestParams.from_json(json)
# print the JSON string representation of the object
print(DiagnosticToolsSpeedtestParams.to_json())

# convert the object into a dict
diagnostic_tools_speedtest_params_dict = diagnostic_tools_speedtest_params_instance.to_dict()
# create an instance of DiagnosticToolsSpeedtestParams from a dict
diagnostic_tools_speedtest_params_from_dict = DiagnosticToolsSpeedtestParams.from_dict(diagnostic_tools_speedtest_params_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


