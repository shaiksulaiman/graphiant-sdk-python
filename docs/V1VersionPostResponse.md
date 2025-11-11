# V1VersionPostResponse


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**updated_version** | [**ManaV2VersionMetadata**](ManaV2VersionMetadata.md) |  | [optional] 

## Example

```python
from graphiant_sdk.models.v1_version_post_response import V1VersionPostResponse

# TODO update the JSON string below
json = "{}"
# create an instance of V1VersionPostResponse from a JSON string
v1_version_post_response_instance = V1VersionPostResponse.from_json(json)
# print the JSON string representation of the object
print(V1VersionPostResponse.to_json())

# convert the object into a dict
v1_version_post_response_dict = v1_version_post_response_instance.to_dict()
# create an instance of V1VersionPostResponse from a dict
v1_version_post_response_from_dict = V1VersionPostResponse.from_dict(v1_version_post_response_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


