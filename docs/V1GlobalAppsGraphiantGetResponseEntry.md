# V1GlobalAppsGraphiantGetResponseEntry


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**app** | [**ManaV2App**](ManaV2App.md) |  | [optional] 
**app_list_reference_count** | **int** |  | [optional] 
**policy_reference_count** | **int** |  | [optional] 

## Example

```python
from graphiant_sdk.models.v1_global_apps_graphiant_get_response_entry import V1GlobalAppsGraphiantGetResponseEntry

# TODO update the JSON string below
json = "{}"
# create an instance of V1GlobalAppsGraphiantGetResponseEntry from a JSON string
v1_global_apps_graphiant_get_response_entry_instance = V1GlobalAppsGraphiantGetResponseEntry.from_json(json)
# print the JSON string representation of the object
print(V1GlobalAppsGraphiantGetResponseEntry.to_json())

# convert the object into a dict
v1_global_apps_graphiant_get_response_entry_dict = v1_global_apps_graphiant_get_response_entry_instance.to_dict()
# create an instance of V1GlobalAppsGraphiantGetResponseEntry from a dict
v1_global_apps_graphiant_get_response_entry_from_dict = V1GlobalAppsGraphiantGetResponseEntry.from_dict(v1_global_apps_graphiant_get_response_entry_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


