# CommonPageInfo


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**current_page** | **int** | The page number we are currently on (required) | [optional] 
**end_cursor** | **str** | Cursor pointing to the last record on the current page | [optional] 
**has_next_page** | **bool** | An indicator whether there is a page after this one in the resultset based on current position | [optional] 
**has_prev_page** | **bool** | An indicator whether there is a page before this one in the resultset based on current position | [optional] 
**start_cursor** | **str** | Cursor pointing to the first record on the current page | [optional] 
**total_pages** | **int** | The number of pages in the complete resultset based on the current length of the page (required) | [optional] 
**total_records** | **int** | Describes the total number of records in the complete resultset (required) | [optional] 

## Example

```python
from graphiant_sdk.models.common_page_info import CommonPageInfo

# TODO update the JSON string below
json = "{}"
# create an instance of CommonPageInfo from a JSON string
common_page_info_instance = CommonPageInfo.from_json(json)
# print the JSON string representation of the object
print(CommonPageInfo.to_json())

# convert the object into a dict
common_page_info_dict = common_page_info_instance.to_dict()
# create an instance of CommonPageInfo from a dict
common_page_info_from_dict = CommonPageInfo.from_dict(common_page_info_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


