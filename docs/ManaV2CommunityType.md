# ManaV2CommunityType


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**additive** | **bool** |  | [optional] 
**community_list** | **List[str]** |  | [optional] 

## Example

```python
from graphiant_sdk.models.mana_v2_community_type import ManaV2CommunityType

# TODO update the JSON string below
json = "{}"
# create an instance of ManaV2CommunityType from a JSON string
mana_v2_community_type_instance = ManaV2CommunityType.from_json(json)
# print the JSON string representation of the object
print(ManaV2CommunityType.to_json())

# convert the object into a dict
mana_v2_community_type_dict = mana_v2_community_type_instance.to_dict()
# create an instance of ManaV2CommunityType from a dict
mana_v2_community_type_from_dict = ManaV2CommunityType.from_dict(mana_v2_community_type_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


