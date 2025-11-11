# ManaV2ExtranetPolicyInput


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**auto** | [**ManaV2ExtranetAutoReverseRoutes**](ManaV2ExtranetAutoReverseRoutes.md) |  | [optional] 
**branches** | [**ManaV2PolicyTargetInput**](ManaV2PolicyTargetInput.md) |  | [optional] 
**description** | **str** |  | [optional] 
**host_prefix_set** | [**ManaV2EnterprisePrefixSetInput**](ManaV2EnterprisePrefixSetInput.md) |  | [optional] 
**manual** | [**ManaV2ExtranetManualReverseRoutes**](ManaV2ExtranetManualReverseRoutes.md) |  | [optional] 
**name** | **str** |  | [optional] 
**shared_prefixes** | **List[str]** |  | [optional] 
**shared_segment** | **int** |  | [optional] 
**source** | [**ManaV2PolicyTargetInput**](ManaV2PolicyTargetInput.md) |  | [optional] 
**target_segments** | **List[int]** |  | [optional] 
**type** | **str** |  | [optional] 

## Example

```python
from graphiant_sdk.models.mana_v2_extranet_policy_input import ManaV2ExtranetPolicyInput

# TODO update the JSON string below
json = "{}"
# create an instance of ManaV2ExtranetPolicyInput from a JSON string
mana_v2_extranet_policy_input_instance = ManaV2ExtranetPolicyInput.from_json(json)
# print the JSON string representation of the object
print(ManaV2ExtranetPolicyInput.to_json())

# convert the object into a dict
mana_v2_extranet_policy_input_dict = mana_v2_extranet_policy_input_instance.to_dict()
# create an instance of ManaV2ExtranetPolicyInput from a dict
mana_v2_extranet_policy_input_from_dict = ManaV2ExtranetPolicyInput.from_dict(mana_v2_extranet_policy_input_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


