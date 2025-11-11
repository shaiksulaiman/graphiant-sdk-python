# ManaV2SiteList


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**name** | **str** |  | [optional] 
**policy_count** | **int** |  | [optional] 
**site_count** | **int** |  | [optional] 
**site_list_id** | **int** |  | [optional] 

## Example

```python
from graphiant_sdk.models.mana_v2_site_list import ManaV2SiteList

# TODO update the JSON string below
json = "{}"
# create an instance of ManaV2SiteList from a JSON string
mana_v2_site_list_instance = ManaV2SiteList.from_json(json)
# print the JSON string representation of the object
print(ManaV2SiteList.to_json())

# convert the object into a dict
mana_v2_site_list_dict = mana_v2_site_list_instance.to_dict()
# create an instance of ManaV2SiteList from a dict
mana_v2_site_list_from_dict = ManaV2SiteList.from_dict(mana_v2_site_list_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


