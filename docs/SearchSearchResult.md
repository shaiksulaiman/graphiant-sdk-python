# SearchSearchResult


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**context** | **str** | A search context from the SearchContext enum (required) | [optional] 
**id** | **int** | A search context from the SearchContext enum (required) | [optional] 
**result** | **str** | A search result (required) | [optional] 

## Example

```python
from graphiant_sdk.models.search_search_result import SearchSearchResult

# TODO update the JSON string below
json = "{}"
# create an instance of SearchSearchResult from a JSON string
search_search_result_instance = SearchSearchResult.from_json(json)
# print the JSON string representation of the object
print(SearchSearchResult.to_json())

# convert the object into a dict
search_search_result_dict = search_search_result_instance.to_dict()
# create an instance of SearchSearchResult from a dict
search_search_result_from_dict = SearchSearchResult.from_dict(search_search_result_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


