# V1GlobalAppsCustomAppIdGetResponse


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**app_config** | [**ManaV2GlobalAppConfig**](ManaV2GlobalAppConfig.md) |  | [optional] 

## Example

```python
from graphiant_sdk.models.v1_global_apps_custom_app_id_get_response import V1GlobalAppsCustomAppIdGetResponse

# TODO update the JSON string below
json = "{}"
# create an instance of V1GlobalAppsCustomAppIdGetResponse from a JSON string
v1_global_apps_custom_app_id_get_response_instance = V1GlobalAppsCustomAppIdGetResponse.from_json(json)
# print the JSON string representation of the object
print(V1GlobalAppsCustomAppIdGetResponse.to_json())

# convert the object into a dict
v1_global_apps_custom_app_id_get_response_dict = v1_global_apps_custom_app_id_get_response_instance.to_dict()
# create an instance of V1GlobalAppsCustomAppIdGetResponse from a dict
v1_global_apps_custom_app_id_get_response_from_dict = V1GlobalAppsCustomAppIdGetResponse.from_dict(v1_global_apps_custom_app_id_get_response_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


