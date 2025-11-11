# V1DiagnosticPacketcaptureStartPostResponse


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**pcap_id** | **int** | Unique identifier for a specific packet capture | [optional] 

## Example

```python
from graphiant_sdk.models.v1_diagnostic_packetcapture_start_post_response import V1DiagnosticPacketcaptureStartPostResponse

# TODO update the JSON string below
json = "{}"
# create an instance of V1DiagnosticPacketcaptureStartPostResponse from a JSON string
v1_diagnostic_packetcapture_start_post_response_instance = V1DiagnosticPacketcaptureStartPostResponse.from_json(json)
# print the JSON string representation of the object
print(V1DiagnosticPacketcaptureStartPostResponse.to_json())

# convert the object into a dict
v1_diagnostic_packetcapture_start_post_response_dict = v1_diagnostic_packetcapture_start_post_response_instance.to_dict()
# create an instance of V1DiagnosticPacketcaptureStartPostResponse from a dict
v1_diagnostic_packetcapture_start_post_response_from_dict = V1DiagnosticPacketcaptureStartPostResponse.from_dict(v1_diagnostic_packetcapture_start_post_response_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


