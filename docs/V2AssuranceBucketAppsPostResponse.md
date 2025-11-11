# V2AssuranceBucketAppsPostResponse


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**apps** | [**List[AssuranceBucketApp]**](AssuranceBucketApp.md) |  | [optional] 

## Example

```python
from graphiant_sdk.models.v2_assurance_bucket_apps_post_response import V2AssuranceBucketAppsPostResponse

# TODO update the JSON string below
json = "{}"
# create an instance of V2AssuranceBucketAppsPostResponse from a JSON string
v2_assurance_bucket_apps_post_response_instance = V2AssuranceBucketAppsPostResponse.from_json(json)
# print the JSON string representation of the object
print(V2AssuranceBucketAppsPostResponse.to_json())

# convert the object into a dict
v2_assurance_bucket_apps_post_response_dict = v2_assurance_bucket_apps_post_response_instance.to_dict()
# create an instance of V2AssuranceBucketAppsPostResponse from a dict
v2_assurance_bucket_apps_post_response_from_dict = V2AssuranceBucketAppsPostResponse.from_dict(v2_assurance_bucket_apps_post_response_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


