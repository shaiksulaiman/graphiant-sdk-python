# V1SiteDetailsSitelistsPostResponse


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**site_lists** | [**List[ManaV2SiteList]**](ManaV2SiteList.md) |  | [optional] 

## Example

```python
from graphiant_sdk.models.v1_site_details_sitelists_post_response import V1SiteDetailsSitelistsPostResponse

# TODO update the JSON string below
json = "{}"
# create an instance of V1SiteDetailsSitelistsPostResponse from a JSON string
v1_site_details_sitelists_post_response_instance = V1SiteDetailsSitelistsPostResponse.from_json(json)
# print the JSON string representation of the object
print(V1SiteDetailsSitelistsPostResponse.to_json())

# convert the object into a dict
v1_site_details_sitelists_post_response_dict = v1_site_details_sitelists_post_response_instance.to_dict()
# create an instance of V1SiteDetailsSitelistsPostResponse from a dict
v1_site_details_sitelists_post_response_from_dict = V1SiteDetailsSitelistsPostResponse.from_dict(v1_site_details_sitelists_post_response_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


