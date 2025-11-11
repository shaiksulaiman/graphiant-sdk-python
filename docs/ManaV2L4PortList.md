# ManaV2L4PortList


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**id** | **int** |  | [optional] 
**name** | **str** |  | [optional] 
**ports** | **List[int]** |  | [optional] 

## Example

```python
from graphiant_sdk.models.mana_v2_l4_port_list import ManaV2L4PortList

# TODO update the JSON string below
json = "{}"
# create an instance of ManaV2L4PortList from a JSON string
mana_v2_l4_port_list_instance = ManaV2L4PortList.from_json(json)
# print the JSON string representation of the object
print(ManaV2L4PortList.to_json())

# convert the object into a dict
mana_v2_l4_port_list_dict = mana_v2_l4_port_list_instance.to_dict()
# create an instance of ManaV2L4PortList from a dict
mana_v2_l4_port_list_from_dict = ManaV2L4PortList.from_dict(mana_v2_l4_port_list_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


