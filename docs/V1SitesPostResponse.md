# V1SitesPostResponse


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**site** | [**ManaV2Site**](ManaV2Site.md) |  | [optional] 

## Example

```python
from graphiant_sdk.models.v1_sites_post_response import V1SitesPostResponse

# TODO update the JSON string below
json = "{}"
# create an instance of V1SitesPostResponse from a JSON string
v1_sites_post_response_instance = V1SitesPostResponse.from_json(json)
# print the JSON string representation of the object
print(V1SitesPostResponse.to_json())

# convert the object into a dict
v1_sites_post_response_dict = v1_sites_post_response_instance.to_dict()
# create an instance of V1SitesPostResponse from a dict
v1_sites_post_response_from_dict = V1SitesPostResponse.from_dict(v1_sites_post_response_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


