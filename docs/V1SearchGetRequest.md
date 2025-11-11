# V1SearchGetRequest


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**filter** | [**SearchSearchFilter**](SearchSearchFilter.md) |  | [optional] 

## Example

```python
from graphiant_sdk.models.v1_search_get_request import V1SearchGetRequest

# TODO update the JSON string below
json = "{}"
# create an instance of V1SearchGetRequest from a JSON string
v1_search_get_request_instance = V1SearchGetRequest.from_json(json)
# print the JSON string representation of the object
print(V1SearchGetRequest.to_json())

# convert the object into a dict
v1_search_get_request_dict = v1_search_get_request_instance.to_dict()
# create an instance of V1SearchGetRequest from a dict
v1_search_get_request_from_dict = V1SearchGetRequest.from_dict(v1_search_get_request_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


