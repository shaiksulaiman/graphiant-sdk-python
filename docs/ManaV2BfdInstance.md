# ManaV2BfdInstance


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**enabled** | **bool** |  | [optional] 
**minimum_interval** | **int** |  | [optional] 
**multiplier** | **int** |  | [optional] 

## Example

```python
from graphiant_sdk.models.mana_v2_bfd_instance import ManaV2BfdInstance

# TODO update the JSON string below
json = "{}"
# create an instance of ManaV2BfdInstance from a JSON string
mana_v2_bfd_instance_instance = ManaV2BfdInstance.from_json(json)
# print the JSON string representation of the object
print(ManaV2BfdInstance.to_json())

# convert the object into a dict
mana_v2_bfd_instance_dict = mana_v2_bfd_instance_instance.to_dict()
# create an instance of ManaV2BfdInstance from a dict
mana_v2_bfd_instance_from_dict = ManaV2BfdInstance.from_dict(mana_v2_bfd_instance_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


