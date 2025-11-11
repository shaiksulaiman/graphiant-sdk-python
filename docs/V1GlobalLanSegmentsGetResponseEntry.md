# V1GlobalLanSegmentsGetResponseEntry


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**associated_interfaces** | **int** |  | [optional] 
**created_at** | [**GoogleProtobufTimestamp**](GoogleProtobufTimestamp.md) |  | [optional] 
**description** | **str** |  | [optional] 
**edge_references** | **int** |  | [optional] 
**id** | **int** |  | [optional] 
**name** | **str** |  | [optional] 
**site_list_references** | **int** |  | [optional] 

## Example

```python
from graphiant_sdk.models.v1_global_lan_segments_get_response_entry import V1GlobalLanSegmentsGetResponseEntry

# TODO update the JSON string below
json = "{}"
# create an instance of V1GlobalLanSegmentsGetResponseEntry from a JSON string
v1_global_lan_segments_get_response_entry_instance = V1GlobalLanSegmentsGetResponseEntry.from_json(json)
# print the JSON string representation of the object
print(V1GlobalLanSegmentsGetResponseEntry.to_json())

# convert the object into a dict
v1_global_lan_segments_get_response_entry_dict = v1_global_lan_segments_get_response_entry_instance.to_dict()
# create an instance of V1GlobalLanSegmentsGetResponseEntry from a dict
v1_global_lan_segments_get_response_entry_from_dict = V1GlobalLanSegmentsGetResponseEntry.from_dict(v1_global_lan_segments_get_response_entry_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


