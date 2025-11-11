# V1GlobalSiteListsIdPutRequest


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**description** | **str** |  | [optional] 
**entries** | [**List[ManaV2SiteListEntry]**](ManaV2SiteListEntry.md) |  | [optional] 

## Example

```python
from graphiant_sdk.models.v1_global_site_lists_id_put_request import V1GlobalSiteListsIdPutRequest

# TODO update the JSON string below
json = "{}"
# create an instance of V1GlobalSiteListsIdPutRequest from a JSON string
v1_global_site_lists_id_put_request_instance = V1GlobalSiteListsIdPutRequest.from_json(json)
# print the JSON string representation of the object
print(V1GlobalSiteListsIdPutRequest.to_json())

# convert the object into a dict
v1_global_site_lists_id_put_request_dict = v1_global_site_lists_id_put_request_instance.to_dict()
# create an instance of V1GlobalSiteListsIdPutRequest from a dict
v1_global_site_lists_id_put_request_from_dict = V1GlobalSiteListsIdPutRequest.from_dict(v1_global_site_lists_id_put_request_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


