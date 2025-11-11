# ManaV2EnterprisePrefixSetData


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**description** | **str** |  | [optional] 
**entries** | [**List[ManaV2EnterprisePrefixSetDataEntry]**](ManaV2EnterprisePrefixSetDataEntry.md) |  | [optional] 
**mode** | **str** |  | [optional] 

## Example

```python
from graphiant_sdk.models.mana_v2_enterprise_prefix_set_data import ManaV2EnterprisePrefixSetData

# TODO update the JSON string below
json = "{}"
# create an instance of ManaV2EnterprisePrefixSetData from a JSON string
mana_v2_enterprise_prefix_set_data_instance = ManaV2EnterprisePrefixSetData.from_json(json)
# print the JSON string representation of the object
print(ManaV2EnterprisePrefixSetData.to_json())

# convert the object into a dict
mana_v2_enterprise_prefix_set_data_dict = mana_v2_enterprise_prefix_set_data_instance.to_dict()
# create an instance of ManaV2EnterprisePrefixSetData from a dict
mana_v2_enterprise_prefix_set_data_from_dict = ManaV2EnterprisePrefixSetData.from_dict(mana_v2_enterprise_prefix_set_data_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


