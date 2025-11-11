# ManaV2EnterprisePrefixSetInput


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**description** | **str** |  | [optional] 
**entries** | [**Dict[str, ManaV2EnterprisePrefixSetInputEntry]**](ManaV2EnterprisePrefixSetInputEntry.md) |  | [optional] 
**id** | **int** |  | [optional] 
**mode** | **str** |  | [optional] 
**name** | **str** |  | [optional] 

## Example

```python
from graphiant_sdk.models.mana_v2_enterprise_prefix_set_input import ManaV2EnterprisePrefixSetInput

# TODO update the JSON string below
json = "{}"
# create an instance of ManaV2EnterprisePrefixSetInput from a JSON string
mana_v2_enterprise_prefix_set_input_instance = ManaV2EnterprisePrefixSetInput.from_json(json)
# print the JSON string representation of the object
print(ManaV2EnterprisePrefixSetInput.to_json())

# convert the object into a dict
mana_v2_enterprise_prefix_set_input_dict = mana_v2_enterprise_prefix_set_input_instance.to_dict()
# create an instance of ManaV2EnterprisePrefixSetInput from a dict
mana_v2_enterprise_prefix_set_input_from_dict = ManaV2EnterprisePrefixSetInput.from_dict(mana_v2_enterprise_prefix_set_input_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


