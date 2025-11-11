# V1DiagnosticPacketcaptureStopPostRequest


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**pcap_id** | **int** | Unique identifier for a specific packet capture | [optional] 

## Example

```python
from graphiant_sdk.models.v1_diagnostic_packetcapture_stop_post_request import V1DiagnosticPacketcaptureStopPostRequest

# TODO update the JSON string below
json = "{}"
# create an instance of V1DiagnosticPacketcaptureStopPostRequest from a JSON string
v1_diagnostic_packetcapture_stop_post_request_instance = V1DiagnosticPacketcaptureStopPostRequest.from_json(json)
# print the JSON string representation of the object
print(V1DiagnosticPacketcaptureStopPostRequest.to_json())

# convert the object into a dict
v1_diagnostic_packetcapture_stop_post_request_dict = v1_diagnostic_packetcapture_stop_post_request_instance.to_dict()
# create an instance of V1DiagnosticPacketcaptureStopPostRequest from a dict
v1_diagnostic_packetcapture_stop_post_request_from_dict = V1DiagnosticPacketcaptureStopPostRequest.from_dict(v1_diagnostic_packetcapture_stop_post_request_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


