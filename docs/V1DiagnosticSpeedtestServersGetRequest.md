# V1DiagnosticSpeedtestServersGetRequest


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**device_id** | **int** | Unique identifier for a specific device (required) | 
**provider** | **str** | supported provider for speedtest utility | [optional] 
**vrf_name** | **str** | Configured VRF Name | [optional] 

## Example

```python
from graphiant_sdk.models.v1_diagnostic_speedtest_servers_get_request import V1DiagnosticSpeedtestServersGetRequest

# TODO update the JSON string below
json = "{}"
# create an instance of V1DiagnosticSpeedtestServersGetRequest from a JSON string
v1_diagnostic_speedtest_servers_get_request_instance = V1DiagnosticSpeedtestServersGetRequest.from_json(json)
# print the JSON string representation of the object
print(V1DiagnosticSpeedtestServersGetRequest.to_json())

# convert the object into a dict
v1_diagnostic_speedtest_servers_get_request_dict = v1_diagnostic_speedtest_servers_get_request_instance.to_dict()
# create an instance of V1DiagnosticSpeedtestServersGetRequest from a dict
v1_diagnostic_speedtest_servers_get_request_from_dict = V1DiagnosticSpeedtestServersGetRequest.from_dict(v1_diagnostic_speedtest_servers_get_request_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


