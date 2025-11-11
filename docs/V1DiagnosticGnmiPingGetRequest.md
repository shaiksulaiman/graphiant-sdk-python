# V1DiagnosticGnmiPingGetRequest


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**device_id** | **int** |  | [optional] 

## Example

```python
from graphiant_sdk.models.v1_diagnostic_gnmi_ping_get_request import V1DiagnosticGnmiPingGetRequest

# TODO update the JSON string below
json = "{}"
# create an instance of V1DiagnosticGnmiPingGetRequest from a JSON string
v1_diagnostic_gnmi_ping_get_request_instance = V1DiagnosticGnmiPingGetRequest.from_json(json)
# print the JSON string representation of the object
print(V1DiagnosticGnmiPingGetRequest.to_json())

# convert the object into a dict
v1_diagnostic_gnmi_ping_get_request_dict = v1_diagnostic_gnmi_ping_get_request_instance.to_dict()
# create an instance of V1DiagnosticGnmiPingGetRequest from a dict
v1_diagnostic_gnmi_ping_get_request_from_dict = V1DiagnosticGnmiPingGetRequest.from_dict(v1_diagnostic_gnmi_ping_get_request_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


