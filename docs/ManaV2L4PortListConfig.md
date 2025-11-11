# ManaV2L4PortListConfig


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**name** | **str** |  | [optional] 
**ports** | **List[int]** |  | [optional] 

## Example

```python
from graphiant_sdk.models.mana_v2_l4_port_list_config import ManaV2L4PortListConfig

# TODO update the JSON string below
json = "{}"
# create an instance of ManaV2L4PortListConfig from a JSON string
mana_v2_l4_port_list_config_instance = ManaV2L4PortListConfig.from_json(json)
# print the JSON string representation of the object
print(ManaV2L4PortListConfig.to_json())

# convert the object into a dict
mana_v2_l4_port_list_config_dict = mana_v2_l4_port_list_config_instance.to_dict()
# create an instance of ManaV2L4PortListConfig from a dict
mana_v2_l4_port_list_config_from_dict = ManaV2L4PortListConfig.from_dict(mana_v2_l4_port_list_config_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


