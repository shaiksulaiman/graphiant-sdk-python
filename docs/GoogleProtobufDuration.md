# GoogleProtobufDuration


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**nanos** | **int** |  | [optional] 
**seconds** | **int** |  | [optional] 

## Example

```python
from graphiant_sdk.models.google_protobuf_duration import GoogleProtobufDuration

# TODO update the JSON string below
json = "{}"
# create an instance of GoogleProtobufDuration from a JSON string
google_protobuf_duration_instance = GoogleProtobufDuration.from_json(json)
# print the JSON string representation of the object
print(GoogleProtobufDuration.to_json())

# convert the object into a dict
google_protobuf_duration_dict = google_protobuf_duration_instance.to_dict()
# create an instance of GoogleProtobufDuration from a dict
google_protobuf_duration_from_dict = GoogleProtobufDuration.from_dict(google_protobuf_duration_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


