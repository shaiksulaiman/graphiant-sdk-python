# V1GlobalAppsCategoriesGetResponseEntry


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**app_count** | **int** |  | [optional] 
**category** | [**ManaV2App**](ManaV2App.md) |  | [optional] 

## Example

```python
from graphiant_sdk.models.v1_global_apps_categories_get_response_entry import V1GlobalAppsCategoriesGetResponseEntry

# TODO update the JSON string below
json = "{}"
# create an instance of V1GlobalAppsCategoriesGetResponseEntry from a JSON string
v1_global_apps_categories_get_response_entry_instance = V1GlobalAppsCategoriesGetResponseEntry.from_json(json)
# print the JSON string representation of the object
print(V1GlobalAppsCategoriesGetResponseEntry.to_json())

# convert the object into a dict
v1_global_apps_categories_get_response_entry_dict = v1_global_apps_categories_get_response_entry_instance.to_dict()
# create an instance of V1GlobalAppsCategoriesGetResponseEntry from a dict
v1_global_apps_categories_get_response_entry_from_dict = V1GlobalAppsCategoriesGetResponseEntry.from_dict(v1_global_apps_categories_get_response_entry_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


