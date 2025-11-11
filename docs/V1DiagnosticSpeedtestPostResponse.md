# V1DiagnosticSpeedtestPostResponse


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**result** | [**DiagnosticToolsSpeedtestResult**](DiagnosticToolsSpeedtestResult.md) |  | [optional] 
**token** | **str** | Token to be sent in subsequent lookup (required) | [optional] 

## Example

```python
from graphiant_sdk.models.v1_diagnostic_speedtest_post_response import V1DiagnosticSpeedtestPostResponse

# TODO update the JSON string below
json = "{}"
# create an instance of V1DiagnosticSpeedtestPostResponse from a JSON string
v1_diagnostic_speedtest_post_response_instance = V1DiagnosticSpeedtestPostResponse.from_json(json)
# print the JSON string representation of the object
print(V1DiagnosticSpeedtestPostResponse.to_json())

# convert the object into a dict
v1_diagnostic_speedtest_post_response_dict = v1_diagnostic_speedtest_post_response_instance.to_dict()
# create an instance of V1DiagnosticSpeedtestPostResponse from a dict
v1_diagnostic_speedtest_post_response_from_dict = V1DiagnosticSpeedtestPostResponse.from_dict(v1_diagnostic_speedtest_post_response_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


