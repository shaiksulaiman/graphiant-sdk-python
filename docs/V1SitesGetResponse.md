# V1SitesGetResponse


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**page_info** | [**CommonPageInfo**](CommonPageInfo.md) |  | [optional] 
**sites** | [**List[ManaV2Site]**](ManaV2Site.md) |  | [optional] 

## Example

```python
from graphiant_sdk.models.v1_sites_get_response import V1SitesGetResponse

# TODO update the JSON string below
json = "{}"
# create an instance of V1SitesGetResponse from a JSON string
v1_sites_get_response_instance = V1SitesGetResponse.from_json(json)
# print the JSON string representation of the object
print(V1SitesGetResponse.to_json())

# convert the object into a dict
v1_sites_get_response_dict = v1_sites_get_response_instance.to_dict()
# create an instance of V1SitesGetResponse from a dict
v1_sites_get_response_from_dict = V1SitesGetResponse.from_dict(v1_sites_get_response_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


