# V1DiagnosticSpeedtestServersGetResponse


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**server** | [**List[DiagnosticToolsSpeedtestServer]**](DiagnosticToolsSpeedtestServer.md) |  | [optional] 

## Example

```python
from graphiant_sdk.models.v1_diagnostic_speedtest_servers_get_response import V1DiagnosticSpeedtestServersGetResponse

# TODO update the JSON string below
json = "{}"
# create an instance of V1DiagnosticSpeedtestServersGetResponse from a JSON string
v1_diagnostic_speedtest_servers_get_response_instance = V1DiagnosticSpeedtestServersGetResponse.from_json(json)
# print the JSON string representation of the object
print(V1DiagnosticSpeedtestServersGetResponse.to_json())

# convert the object into a dict
v1_diagnostic_speedtest_servers_get_response_dict = v1_diagnostic_speedtest_servers_get_response_instance.to_dict()
# create an instance of V1DiagnosticSpeedtestServersGetResponse from a dict
v1_diagnostic_speedtest_servers_get_response_from_dict = V1DiagnosticSpeedtestServersGetResponse.from_dict(v1_diagnostic_speedtest_servers_get_response_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


