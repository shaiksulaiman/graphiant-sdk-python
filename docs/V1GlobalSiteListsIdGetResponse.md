# V1GlobalSiteListsIdGetResponse


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**description** | **str** |  | [optional] 
**entries** | [**List[ManaV2SiteListEntry]**](ManaV2SiteListEntry.md) |  | [optional] 

## Example

```python
from graphiant_sdk.models.v1_global_site_lists_id_get_response import V1GlobalSiteListsIdGetResponse

# TODO update the JSON string below
json = "{}"
# create an instance of V1GlobalSiteListsIdGetResponse from a JSON string
v1_global_site_lists_id_get_response_instance = V1GlobalSiteListsIdGetResponse.from_json(json)
# print the JSON string representation of the object
print(V1GlobalSiteListsIdGetResponse.to_json())

# convert the object into a dict
v1_global_site_lists_id_get_response_dict = v1_global_site_lists_id_get_response_instance.to_dict()
# create an instance of V1GlobalSiteListsIdGetResponse from a dict
v1_global_site_lists_id_get_response_from_dict = V1GlobalSiteListsIdGetResponse.from_dict(v1_global_site_lists_id_get_response_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


