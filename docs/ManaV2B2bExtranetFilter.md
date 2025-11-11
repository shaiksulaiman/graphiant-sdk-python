# ManaV2B2bExtranetFilter


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**customers** | [**List[ManaV2DomainCategory]**](ManaV2DomainCategory.md) |  | [optional] 
**sites** | [**List[ManaV2DomainCategory]**](ManaV2DomainCategory.md) |  | [optional] 

## Example

```python
from graphiant_sdk.models.mana_v2_b2b_extranet_filter import ManaV2B2bExtranetFilter

# TODO update the JSON string below
json = "{}"
# create an instance of ManaV2B2bExtranetFilter from a JSON string
mana_v2_b2b_extranet_filter_instance = ManaV2B2bExtranetFilter.from_json(json)
# print the JSON string representation of the object
print(ManaV2B2bExtranetFilter.to_json())

# convert the object into a dict
mana_v2_b2b_extranet_filter_dict = mana_v2_b2b_extranet_filter_instance.to_dict()
# create an instance of ManaV2B2bExtranetFilter from a dict
mana_v2_b2b_extranet_filter_from_dict = ManaV2B2bExtranetFilter.from_dict(mana_v2_b2b_extranet_filter_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


