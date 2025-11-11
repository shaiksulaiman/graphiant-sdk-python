# V1DiagnosticTraceroutePostResponse


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**result** | [**DiagnosticToolsDiagnosticResult**](DiagnosticToolsDiagnosticResult.md) |  | [optional] 
**token** | **str** | Token to be sent in subsequent lookup (required) | [optional] 

## Example

```python
from graphiant_sdk.models.v1_diagnostic_traceroute_post_response import V1DiagnosticTraceroutePostResponse

# TODO update the JSON string below
json = "{}"
# create an instance of V1DiagnosticTraceroutePostResponse from a JSON string
v1_diagnostic_traceroute_post_response_instance = V1DiagnosticTraceroutePostResponse.from_json(json)
# print the JSON string representation of the object
print(V1DiagnosticTraceroutePostResponse.to_json())

# convert the object into a dict
v1_diagnostic_traceroute_post_response_dict = v1_diagnostic_traceroute_post_response_instance.to_dict()
# create an instance of V1DiagnosticTraceroutePostResponse from a dict
v1_diagnostic_traceroute_post_response_from_dict = V1DiagnosticTraceroutePostResponse.from_dict(v1_diagnostic_traceroute_post_response_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


