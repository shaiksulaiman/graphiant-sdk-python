# V1SitesDetailsGetResponse


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**sites** | [**List[ManaV2Site]**](ManaV2Site.md) |  | [optional] 

## Example

```python
from graphiant_sdk.models.v1_sites_details_get_response import V1SitesDetailsGetResponse

# TODO update the JSON string below
json = "{}"
# create an instance of V1SitesDetailsGetResponse from a JSON string
v1_sites_details_get_response_instance = V1SitesDetailsGetResponse.from_json(json)
# print the JSON string representation of the object
print(V1SitesDetailsGetResponse.to_json())

# convert the object into a dict
v1_sites_details_get_response_dict = v1_sites_details_get_response_instance.to_dict()
# create an instance of V1SitesDetailsGetResponse from a dict
v1_sites_details_get_response_from_dict = V1SitesDetailsGetResponse.from_dict(v1_sites_details_get_response_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


