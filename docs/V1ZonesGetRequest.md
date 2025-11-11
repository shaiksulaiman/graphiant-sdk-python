# V1ZonesGetRequest


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**device_id** | **int** |  | [optional] 
**filter** | **str** |  | [optional] 
**page_request** | [**CommonPageRequest**](CommonPageRequest.md) |  | [optional] 

## Example

```python
from graphiant_sdk.models.v1_zones_get_request import V1ZonesGetRequest

# TODO update the JSON string below
json = "{}"
# create an instance of V1ZonesGetRequest from a JSON string
v1_zones_get_request_instance = V1ZonesGetRequest.from_json(json)
# print the JSON string representation of the object
print(V1ZonesGetRequest.to_json())

# convert the object into a dict
v1_zones_get_request_dict = v1_zones_get_request_instance.to_dict()
# create an instance of V1ZonesGetRequest from a dict
v1_zones_get_request_from_dict = V1ZonesGetRequest.from_dict(v1_zones_get_request_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


