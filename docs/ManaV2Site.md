# ManaV2Site


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**address** | **str** |  | [optional] 
**created_at** | [**GoogleProtobufTimestamp**](GoogleProtobufTimestamp.md) |  | [optional] 
**devices** | [**List[ManaV2SiteDeviceStub]**](ManaV2SiteDeviceStub.md) |  | [optional] 
**edge_count** | **int** |  | [optional] 
**id** | **int** |  | [optional] 
**location** | [**ManaV2Location**](ManaV2Location.md) |  | [optional] 
**name** | **str** |  | [optional] 
**notes** | **str** |  | [optional] 
**policy_reference_count** | **int** |  | [optional] 
**policy_tag** | [**ManaV2SingleRouteTag**](ManaV2SingleRouteTag.md) |  | [optional] 
**segment_count** | **int** |  | [optional] 
**site_list_reference_count** | **int** |  | [optional] 
**tags** | **List[str]** |  | [optional] 
**updated_at** | [**GoogleProtobufTimestamp**](GoogleProtobufTimestamp.md) |  | [optional] 

## Example

```python
from graphiant_sdk.models.mana_v2_site import ManaV2Site

# TODO update the JSON string below
json = "{}"
# create an instance of ManaV2Site from a JSON string
mana_v2_site_instance = ManaV2Site.from_json(json)
# print the JSON string representation of the object
print(ManaV2Site.to_json())

# convert the object into a dict
mana_v2_site_dict = mana_v2_site_instance.to_dict()
# create an instance of ManaV2Site from a dict
mana_v2_site_from_dict = ManaV2Site.from_dict(mana_v2_site_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


