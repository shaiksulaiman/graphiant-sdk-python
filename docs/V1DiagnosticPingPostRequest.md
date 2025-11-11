# V1DiagnosticPingPostRequest


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**device_id** | **int** | Valid Provisioned device ID (required) | 
**params** | [**DiagnosticToolsDiagnosticParams**](DiagnosticToolsDiagnosticParams.md) |  | [optional] 
**token** | **str** | Identifier which was received in initial response | [optional] 
**transport_type** | **str** | ICMP or TCP (required) | 

## Example

```python
from graphiant_sdk.models.v1_diagnostic_ping_post_request import V1DiagnosticPingPostRequest

# TODO update the JSON string below
json = "{}"
# create an instance of V1DiagnosticPingPostRequest from a JSON string
v1_diagnostic_ping_post_request_instance = V1DiagnosticPingPostRequest.from_json(json)
# print the JSON string representation of the object
print(V1DiagnosticPingPostRequest.to_json())

# convert the object into a dict
v1_diagnostic_ping_post_request_dict = v1_diagnostic_ping_post_request_instance.to_dict()
# create an instance of V1DiagnosticPingPostRequest from a dict
v1_diagnostic_ping_post_request_from_dict = V1DiagnosticPingPostRequest.from_dict(v1_diagnostic_ping_post_request_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


