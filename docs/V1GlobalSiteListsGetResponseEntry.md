# V1GlobalSiteListsGetResponseEntry


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**created_at** | [**GoogleProtobufTimestamp**](GoogleProtobufTimestamp.md) |  | [optional] 
**description** | **str** |  | [optional] 
**edge_references** | **int** |  | [optional] 
**id** | **int** |  | [optional] 
**name** | **str** |  | [optional] 
**policy_references** | **int** |  | [optional] 
**site_list_references** | **int** |  | [optional] 

## Example

```python
from graphiant_sdk.models.v1_global_site_lists_get_response_entry import V1GlobalSiteListsGetResponseEntry

# TODO update the JSON string below
json = "{}"
# create an instance of V1GlobalSiteListsGetResponseEntry from a JSON string
v1_global_site_lists_get_response_entry_instance = V1GlobalSiteListsGetResponseEntry.from_json(json)
# print the JSON string representation of the object
print(V1GlobalSiteListsGetResponseEntry.to_json())

# convert the object into a dict
v1_global_site_lists_get_response_entry_dict = v1_global_site_lists_get_response_entry_instance.to_dict()
# create an instance of V1GlobalSiteListsGetResponseEntry from a dict
v1_global_site_lists_get_response_entry_from_dict = V1GlobalSiteListsGetResponseEntry.from_dict(v1_global_site_lists_get_response_entry_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


