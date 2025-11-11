# V1DiagnosticArchivesDeviceIdGetResponse


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**archives** | [**List[DiagnosticToolsArchive]**](DiagnosticToolsArchive.md) |  | [optional] 

## Example

```python
from graphiant_sdk.models.v1_diagnostic_archives_device_id_get_response import V1DiagnosticArchivesDeviceIdGetResponse

# TODO update the JSON string below
json = "{}"
# create an instance of V1DiagnosticArchivesDeviceIdGetResponse from a JSON string
v1_diagnostic_archives_device_id_get_response_instance = V1DiagnosticArchivesDeviceIdGetResponse.from_json(json)
# print the JSON string representation of the object
print(V1DiagnosticArchivesDeviceIdGetResponse.to_json())

# convert the object into a dict
v1_diagnostic_archives_device_id_get_response_dict = v1_diagnostic_archives_device_id_get_response_instance.to_dict()
# create an instance of V1DiagnosticArchivesDeviceIdGetResponse from a dict
v1_diagnostic_archives_device_id_get_response_from_dict = V1DiagnosticArchivesDeviceIdGetResponse.from_dict(v1_diagnostic_archives_device_id_get_response_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


