# V1GlobalAppsCustomGetResponseEntry


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**app** | [**ManaV2App**](ManaV2App.md) |  | [optional] 
**app_config** | [**ManaV2GlobalAppConfig**](ManaV2GlobalAppConfig.md) |  | [optional] 
**app_list_reference_count** | **int** |  | [optional] 
**policy_reference_count** | **int** |  | [optional] 

## Example

```python
from graphiant_sdk.models.v1_global_apps_custom_get_response_entry import V1GlobalAppsCustomGetResponseEntry

# TODO update the JSON string below
json = "{}"
# create an instance of V1GlobalAppsCustomGetResponseEntry from a JSON string
v1_global_apps_custom_get_response_entry_instance = V1GlobalAppsCustomGetResponseEntry.from_json(json)
# print the JSON string representation of the object
print(V1GlobalAppsCustomGetResponseEntry.to_json())

# convert the object into a dict
v1_global_apps_custom_get_response_entry_dict = v1_global_apps_custom_get_response_entry_instance.to_dict()
# create an instance of V1GlobalAppsCustomGetResponseEntry from a dict
v1_global_apps_custom_get_response_entry_from_dict = V1GlobalAppsCustomGetResponseEntry.from_dict(v1_global_apps_custom_get_response_entry_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


