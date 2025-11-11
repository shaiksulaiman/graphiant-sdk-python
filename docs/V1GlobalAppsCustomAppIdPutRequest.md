# V1GlobalAppsCustomAppIdPutRequest


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**app_config** | [**ManaV2GlobalAppConfig**](ManaV2GlobalAppConfig.md) |  | [optional] 

## Example

```python
from graphiant_sdk.models.v1_global_apps_custom_app_id_put_request import V1GlobalAppsCustomAppIdPutRequest

# TODO update the JSON string below
json = "{}"
# create an instance of V1GlobalAppsCustomAppIdPutRequest from a JSON string
v1_global_apps_custom_app_id_put_request_instance = V1GlobalAppsCustomAppIdPutRequest.from_json(json)
# print the JSON string representation of the object
print(V1GlobalAppsCustomAppIdPutRequest.to_json())

# convert the object into a dict
v1_global_apps_custom_app_id_put_request_dict = v1_global_apps_custom_app_id_put_request_instance.to_dict()
# create an instance of V1GlobalAppsCustomAppIdPutRequest from a dict
v1_global_apps_custom_app_id_put_request_from_dict = V1GlobalAppsCustomAppIdPutRequest.from_dict(v1_global_apps_custom_app_id_put_request_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


