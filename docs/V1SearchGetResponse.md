# V1SearchGetResponse


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**results** | [**List[SearchSearchResult]**](SearchSearchResult.md) |  | [optional] 

## Example

```python
from graphiant_sdk.models.v1_search_get_response import V1SearchGetResponse

# TODO update the JSON string below
json = "{}"
# create an instance of V1SearchGetResponse from a JSON string
v1_search_get_response_instance = V1SearchGetResponse.from_json(json)
# print the JSON string representation of the object
print(V1SearchGetResponse.to_json())

# convert the object into a dict
v1_search_get_response_dict = v1_search_get_response_instance.to_dict()
# create an instance of V1SearchGetResponse from a dict
v1_search_get_response_from_dict = V1SearchGetResponse.from_dict(v1_search_get_response_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


