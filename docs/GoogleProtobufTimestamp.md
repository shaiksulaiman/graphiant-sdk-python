# GoogleProtobufTimestamp


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**nanos** | **int** |  | [optional] 
**seconds** | **int** |  | [optional] 

## Example

```python
from graphiant_sdk.models.google_protobuf_timestamp import GoogleProtobufTimestamp

# TODO update the JSON string below
json = "{}"
# create an instance of GoogleProtobufTimestamp from a JSON string
google_protobuf_timestamp_instance = GoogleProtobufTimestamp.from_json(json)
# print the JSON string representation of the object
print(GoogleProtobufTimestamp.to_json())

# convert the object into a dict
google_protobuf_timestamp_dict = google_protobuf_timestamp_instance.to_dict()
# create an instance of GoogleProtobufTimestamp from a dict
google_protobuf_timestamp_from_dict = GoogleProtobufTimestamp.from_dict(google_protobuf_timestamp_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


