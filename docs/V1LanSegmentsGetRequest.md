# V1LanSegmentsGetRequest


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**device_id** | **int** |  | [optional] 
**filter** | **str** |  | [optional] 
**page_request** | [**CommonPageRequest**](CommonPageRequest.md) |  | [optional] 

## Example

```python
from graphiant_sdk.models.v1_lan_segments_get_request import V1LanSegmentsGetRequest

# TODO update the JSON string below
json = "{}"
# create an instance of V1LanSegmentsGetRequest from a JSON string
v1_lan_segments_get_request_instance = V1LanSegmentsGetRequest.from_json(json)
# print the JSON string representation of the object
print(V1LanSegmentsGetRequest.to_json())

# convert the object into a dict
v1_lan_segments_get_request_dict = v1_lan_segments_get_request_instance.to_dict()
# create an instance of V1LanSegmentsGetRequest from a dict
v1_lan_segments_get_request_from_dict = V1LanSegmentsGetRequest.from_dict(v1_lan_segments_get_request_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


