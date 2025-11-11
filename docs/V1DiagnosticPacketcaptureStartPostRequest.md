# V1DiagnosticPacketcaptureStartPostRequest


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**device_id** | **int** | Unique identifier for a specific device (required) | 
**duration** | **int** | Packet capture duration. Accepted values are 30, 60, 180 (required) | 
**filter** | [**DiagnosticToolsPCapFilter**](DiagnosticToolsPCapFilter.md) |  | [optional] 
**max_packet_counter** | **int** | Packet capture limit. | [optional] 
**target** | [**DiagnosticToolsTargetType**](DiagnosticToolsTargetType.md) |  | 

## Example

```python
from graphiant_sdk.models.v1_diagnostic_packetcapture_start_post_request import V1DiagnosticPacketcaptureStartPostRequest

# TODO update the JSON string below
json = "{}"
# create an instance of V1DiagnosticPacketcaptureStartPostRequest from a JSON string
v1_diagnostic_packetcapture_start_post_request_instance = V1DiagnosticPacketcaptureStartPostRequest.from_json(json)
# print the JSON string representation of the object
print(V1DiagnosticPacketcaptureStartPostRequest.to_json())

# convert the object into a dict
v1_diagnostic_packetcapture_start_post_request_dict = v1_diagnostic_packetcapture_start_post_request_instance.to_dict()
# create an instance of V1DiagnosticPacketcaptureStartPostRequest from a dict
v1_diagnostic_packetcapture_start_post_request_from_dict = V1DiagnosticPacketcaptureStartPostRequest.from_dict(v1_diagnostic_packetcapture_start_post_request_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


