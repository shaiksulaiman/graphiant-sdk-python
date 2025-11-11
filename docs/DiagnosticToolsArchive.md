# DiagnosticToolsArchive


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**archive_file_name** | **str** | The archive file name | [optional] 
**archive_id** | **int** | Unique identifier for a specific archive | [optional] 
**archive_url** | **str** | The URL to download this archive | [optional] 
**created** | [**GoogleProtobufTimestamp**](GoogleProtobufTimestamp.md) |  | [optional] 
**creator** | **str** | The user who requested the generation of this archive | [optional] 
**description** | **str** | Description of the requested archive | [optional] 
**progress** | **int** | The upload progress of the requested debug archive in percentage | [optional] 
**status** | **str** | The status of the requested debug archive | [optional] 
**type** | **str** | The type of the archive | [optional] 

## Example

```python
from graphiant_sdk.models.diagnostic_tools_archive import DiagnosticToolsArchive

# TODO update the JSON string below
json = "{}"
# create an instance of DiagnosticToolsArchive from a JSON string
diagnostic_tools_archive_instance = DiagnosticToolsArchive.from_json(json)
# print the JSON string representation of the object
print(DiagnosticToolsArchive.to_json())

# convert the object into a dict
diagnostic_tools_archive_dict = diagnostic_tools_archive_instance.to_dict()
# create an instance of DiagnosticToolsArchive from a dict
diagnostic_tools_archive_from_dict = DiagnosticToolsArchive.from_dict(diagnostic_tools_archive_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


