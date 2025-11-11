# ManaV2SiteListEntry


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**regular** | **int** |  | [optional] 
**tag** | [**ManaV2RouteTagId**](ManaV2RouteTagId.md) |  | [optional] 

## Example

```python
from graphiant_sdk.models.mana_v2_site_list_entry import ManaV2SiteListEntry

# TODO update the JSON string below
json = "{}"
# create an instance of ManaV2SiteListEntry from a JSON string
mana_v2_site_list_entry_instance = ManaV2SiteListEntry.from_json(json)
# print the JSON string representation of the object
print(ManaV2SiteListEntry.to_json())

# convert the object into a dict
mana_v2_site_list_entry_dict = mana_v2_site_list_entry_instance.to_dict()
# create an instance of ManaV2SiteListEntry from a dict
mana_v2_site_list_entry_from_dict = ManaV2SiteListEntry.from_dict(mana_v2_site_list_entry_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


