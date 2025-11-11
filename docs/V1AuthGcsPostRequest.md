# V1AuthGcsPostRequest


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**gcs_name** | **str** |  | 
**api_key** | **str** |  | 

## Example

```python
from graphiant_sdk.models.v1_auth_gcs_post_request import V1AuthGcsPostRequest

# TODO update the JSON string below
json = "{}"
# create an instance of V1AuthGcsPostRequest from a JSON string
v1_auth_gcs_post_request_instance = V1AuthGcsPostRequest.from_json(json)
# print the JSON string representation of the object
print(V1AuthGcsPostRequest.to_json())

# convert the object into a dict
v1_auth_gcs_post_request_dict = v1_auth_gcs_post_request_instance.to_dict()
# create an instance of V1AuthGcsPostRequest from a dict
v1_auth_gcs_post_request_from_dict = V1AuthGcsPostRequest.from_dict(v1_auth_gcs_post_request_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


