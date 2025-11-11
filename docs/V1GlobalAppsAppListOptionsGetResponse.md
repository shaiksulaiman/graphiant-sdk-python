# V1GlobalAppsAppListOptionsGetResponse


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**apps** | [**List[ManaV2App]**](ManaV2App.md) |  | [optional] 

## Example

```python
from graphiant_sdk.models.v1_global_apps_app_list_options_get_response import V1GlobalAppsAppListOptionsGetResponse

# TODO update the JSON string below
json = "{}"
# create an instance of V1GlobalAppsAppListOptionsGetResponse from a JSON string
v1_global_apps_app_list_options_get_response_instance = V1GlobalAppsAppListOptionsGetResponse.from_json(json)
# print the JSON string representation of the object
print(V1GlobalAppsAppListOptionsGetResponse.to_json())

# convert the object into a dict
v1_global_apps_app_list_options_get_response_dict = v1_global_apps_app_list_options_get_response_instance.to_dict()
# create an instance of V1GlobalAppsAppListOptionsGetResponse from a dict
v1_global_apps_app_list_options_get_response_from_dict = V1GlobalAppsAppListOptionsGetResponse.from_dict(v1_global_apps_app_list_options_get_response_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


