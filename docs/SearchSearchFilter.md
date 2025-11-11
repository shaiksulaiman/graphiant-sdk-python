# SearchSearchFilter


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**role** | **str** |  | [optional] 
**site_name** | **str** |  | [optional] 
**status** | **str** | Status of the device, valid values are staging, active, inactive (required) | 

## Example

```python
from graphiant_sdk.models.search_search_filter import SearchSearchFilter

# TODO update the JSON string below
json = "{}"
# create an instance of SearchSearchFilter from a JSON string
search_search_filter_instance = SearchSearchFilter.from_json(json)
# print the JSON string representation of the object
print(SearchSearchFilter.to_json())

# convert the object into a dict
search_search_filter_dict = search_search_filter_instance.to_dict()
# create an instance of SearchSearchFilter from a dict
search_search_filter_from_dict = SearchSearchFilter.from_dict(search_search_filter_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


