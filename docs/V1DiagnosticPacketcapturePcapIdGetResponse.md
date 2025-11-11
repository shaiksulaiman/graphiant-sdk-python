# V1DiagnosticPacketcapturePcapIdGetResponse


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**failure_reason** | **str** | Error message if the packet capture generation/upload failed | [optional] 
**file_name** | **str** | The PCap file name. | [optional] 
**status** | **str** | The status of the requested packet capture | [optional] 
**upload_progress** | **int** | upload progress in percentage | [optional] 
**url** | **str** | The URL to download this packet capture. | [optional] 

## Example

```python
from graphiant_sdk.models.v1_diagnostic_packetcapture_pcap_id_get_response import V1DiagnosticPacketcapturePcapIdGetResponse

# TODO update the JSON string below
json = "{}"
# create an instance of V1DiagnosticPacketcapturePcapIdGetResponse from a JSON string
v1_diagnostic_packetcapture_pcap_id_get_response_instance = V1DiagnosticPacketcapturePcapIdGetResponse.from_json(json)
# print the JSON string representation of the object
print(V1DiagnosticPacketcapturePcapIdGetResponse.to_json())

# convert the object into a dict
v1_diagnostic_packetcapture_pcap_id_get_response_dict = v1_diagnostic_packetcapture_pcap_id_get_response_instance.to_dict()
# create an instance of V1DiagnosticPacketcapturePcapIdGetResponse from a dict
v1_diagnostic_packetcapture_pcap_id_get_response_from_dict = V1DiagnosticPacketcapturePcapIdGetResponse.from_dict(v1_diagnostic_packetcapture_pcap_id_get_response_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


