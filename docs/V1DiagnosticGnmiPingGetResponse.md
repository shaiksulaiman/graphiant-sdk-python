# V1DiagnosticGnmiPingGetResponse


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**results** | [**List[V1DiagnosticGnmiPingGetResponseResult]**](V1DiagnosticGnmiPingGetResponseResult.md) |  | [optional] 

## Example

```python
from graphiant_sdk.models.v1_diagnostic_gnmi_ping_get_response import V1DiagnosticGnmiPingGetResponse

# TODO update the JSON string below
json = "{}"
# create an instance of V1DiagnosticGnmiPingGetResponse from a JSON string
v1_diagnostic_gnmi_ping_get_response_instance = V1DiagnosticGnmiPingGetResponse.from_json(json)
# print the JSON string representation of the object
print(V1DiagnosticGnmiPingGetResponse.to_json())

# convert the object into a dict
v1_diagnostic_gnmi_ping_get_response_dict = v1_diagnostic_gnmi_ping_get_response_instance.to_dict()
# create an instance of V1DiagnosticGnmiPingGetResponse from a dict
v1_diagnostic_gnmi_ping_get_response_from_dict = V1DiagnosticGnmiPingGetResponse.from_dict(v1_diagnostic_gnmi_ping_get_response_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


