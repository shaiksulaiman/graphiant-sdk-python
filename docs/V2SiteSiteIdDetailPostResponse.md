# V2SiteSiteIdDetailPostResponse


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**site** | [**StatsmonV2SiteInfo**](StatsmonV2SiteInfo.md) |  | [optional] 
**snapshots** | [**List[GoogleProtobufTimestamp]**](GoogleProtobufTimestamp.md) |  | [optional] 

## Example

```python
from graphiant_sdk.models.v2_site_site_id_detail_post_response import V2SiteSiteIdDetailPostResponse

# TODO update the JSON string below
json = "{}"
# create an instance of V2SiteSiteIdDetailPostResponse from a JSON string
v2_site_site_id_detail_post_response_instance = V2SiteSiteIdDetailPostResponse.from_json(json)
# print the JSON string representation of the object
print(V2SiteSiteIdDetailPostResponse.to_json())

# convert the object into a dict
v2_site_site_id_detail_post_response_dict = v2_site_site_id_detail_post_response_instance.to_dict()
# create an instance of V2SiteSiteIdDetailPostResponse from a dict
v2_site_site_id_detail_post_response_from_dict = V2SiteSiteIdDetailPostResponse.from_dict(v2_site_site_id_detail_post_response_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


