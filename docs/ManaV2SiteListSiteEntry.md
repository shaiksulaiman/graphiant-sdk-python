# ManaV2SiteListSiteEntry


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**created_at** | [**GoogleProtobufTimestamp**](GoogleProtobufTimestamp.md) |  | [optional] 
**edge_references** | **int** |  | [optional] 
**site_name** | **str** |  | [optional] 
**tag** | [**List[ManaV2RouteTagId]**](ManaV2RouteTagId.md) |  | [optional] 

## Example

```python
from graphiant_sdk.models.mana_v2_site_list_site_entry import ManaV2SiteListSiteEntry

# TODO update the JSON string below
json = "{}"
# create an instance of ManaV2SiteListSiteEntry from a JSON string
mana_v2_site_list_site_entry_instance = ManaV2SiteListSiteEntry.from_json(json)
# print the JSON string representation of the object
print(ManaV2SiteListSiteEntry.to_json())

# convert the object into a dict
mana_v2_site_list_site_entry_dict = mana_v2_site_list_site_entry_instance.to_dict()
# create an instance of ManaV2SiteListSiteEntry from a dict
mana_v2_site_list_site_entry_from_dict = ManaV2SiteListSiteEntry.from_dict(mana_v2_site_list_site_entry_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


