# V1DiagnosticGnmiPingGetResponseResult


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**address** | **str** | Address of the device on which the test was performed | [optional] 
**error** | **str** | If error is empty, the ping is success | [optional] 
**rtt** | [**GoogleProtobufDuration**](GoogleProtobufDuration.md) |  | [optional] 
**tt_device_id** | **int** |  | [optional] 

## Example

```python
from graphiant_sdk.models.v1_diagnostic_gnmi_ping_get_response_result import V1DiagnosticGnmiPingGetResponseResult

# TODO update the JSON string below
json = "{}"
# create an instance of V1DiagnosticGnmiPingGetResponseResult from a JSON string
v1_diagnostic_gnmi_ping_get_response_result_instance = V1DiagnosticGnmiPingGetResponseResult.from_json(json)
# print the JSON string representation of the object
print(V1DiagnosticGnmiPingGetResponseResult.to_json())

# convert the object into a dict
v1_diagnostic_gnmi_ping_get_response_result_dict = v1_diagnostic_gnmi_ping_get_response_result_instance.to_dict()
# create an instance of V1DiagnosticGnmiPingGetResponseResult from a dict
v1_diagnostic_gnmi_ping_get_response_result_from_dict = V1DiagnosticGnmiPingGetResponseResult.from_dict(v1_diagnostic_gnmi_ping_get_response_result_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


