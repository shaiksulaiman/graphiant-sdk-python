# V1GlobalAppsCustomPostResponse


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**app_identifier** | [**ManaV2AppIdentifier**](ManaV2AppIdentifier.md) |  | [optional] 

## Example

```python
from graphiant_sdk.models.v1_global_apps_custom_post_response import V1GlobalAppsCustomPostResponse

# TODO update the JSON string below
json = "{}"
# create an instance of V1GlobalAppsCustomPostResponse from a JSON string
v1_global_apps_custom_post_response_instance = V1GlobalAppsCustomPostResponse.from_json(json)
# print the JSON string representation of the object
print(V1GlobalAppsCustomPostResponse.to_json())

# convert the object into a dict
v1_global_apps_custom_post_response_dict = v1_global_apps_custom_post_response_instance.to_dict()
# create an instance of V1GlobalAppsCustomPostResponse from a dict
v1_global_apps_custom_post_response_from_dict = V1GlobalAppsCustomPostResponse.from_dict(v1_global_apps_custom_post_response_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


