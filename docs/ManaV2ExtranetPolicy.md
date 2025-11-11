# ManaV2ExtranetPolicy


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**auto** | [**ManaV2ExtranetAutoReverseRoutes**](ManaV2ExtranetAutoReverseRoutes.md) |  | [optional] 
**branches** | [**ManaV2PolicyTarget**](ManaV2PolicyTarget.md) |  | [optional] 
**created_at** | [**GoogleProtobufTimestamp**](GoogleProtobufTimestamp.md) |  | [optional] 
**created_by** | **str** |  | [optional] 
**description** | **str** |  | [optional] 
**host_prefix_set** | [**ManaV2EnterprisePrefixSet**](ManaV2EnterprisePrefixSet.md) |  | [optional] 
**id** | **int** |  | [optional] 
**manual** | [**ManaV2ExtranetManualReverseRoutes**](ManaV2ExtranetManualReverseRoutes.md) |  | [optional] 
**name** | **str** |  | [optional] 
**shared_prefixes** | **List[str]** |  | [optional] 
**shared_segment** | [**ManaV2Vrf**](ManaV2Vrf.md) |  | [optional] 
**source** | [**ManaV2PolicyTarget**](ManaV2PolicyTarget.md) |  | [optional] 
**target_segments** | [**List[ManaV2Vrf]**](ManaV2Vrf.md) |  | [optional] 
**type** | **str** |  | [optional] 
**updated_at** | [**GoogleProtobufTimestamp**](GoogleProtobufTimestamp.md) |  | [optional] 

## Example

```python
from graphiant_sdk.models.mana_v2_extranet_policy import ManaV2ExtranetPolicy

# TODO update the JSON string below
json = "{}"
# create an instance of ManaV2ExtranetPolicy from a JSON string
mana_v2_extranet_policy_instance = ManaV2ExtranetPolicy.from_json(json)
# print the JSON string representation of the object
print(ManaV2ExtranetPolicy.to_json())

# convert the object into a dict
mana_v2_extranet_policy_dict = mana_v2_extranet_policy_instance.to_dict()
# create an instance of ManaV2ExtranetPolicy from a dict
mana_v2_extranet_policy_from_dict = ManaV2ExtranetPolicy.from_dict(mana_v2_extranet_policy_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


