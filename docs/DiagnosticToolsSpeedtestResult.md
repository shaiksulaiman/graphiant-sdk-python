# DiagnosticToolsSpeedtestResult


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**avg_ping_time** | **float** | Avg Ping Time in milli seconds (required) | [optional] 
**date_time** | [**GoogleProtobufTimestamp**](GoogleProtobufTimestamp.md) |  | [optional] 
**download_speed** | **float** | Download speed in Mbps (required) | [optional] 
**isp** | **str** | ISP details (required) | [optional] 
**max_ping_time** | **float** | Max PingTime in milli seconds (required) | [optional] 
**min_ping_time** | **float** | Min Ping Time in milli seconds (required) | [optional] 
**result** | **str** | Status of the speedtest operation (required) | [optional] 
**server_details** | [**DiagnosticToolsSpeedtestServer**](DiagnosticToolsSpeedtestServer.md) |  | [optional] 
**upload_speed** | **float** | Upload speed in Mbps (required) | [optional] 

## Example

```python
from graphiant_sdk.models.diagnostic_tools_speedtest_result import DiagnosticToolsSpeedtestResult

# TODO update the JSON string below
json = "{}"
# create an instance of DiagnosticToolsSpeedtestResult from a JSON string
diagnostic_tools_speedtest_result_instance = DiagnosticToolsSpeedtestResult.from_json(json)
# print the JSON string representation of the object
print(DiagnosticToolsSpeedtestResult.to_json())

# convert the object into a dict
diagnostic_tools_speedtest_result_dict = diagnostic_tools_speedtest_result_instance.to_dict()
# create an instance of DiagnosticToolsSpeedtestResult from a dict
diagnostic_tools_speedtest_result_from_dict = DiagnosticToolsSpeedtestResult.from_dict(diagnostic_tools_speedtest_result_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


