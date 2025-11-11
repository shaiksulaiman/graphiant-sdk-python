# ManaV2CircuitInterface


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**admin_status** | **bool** |  | [optional] 
**id** | **int** |  | [optional] 
**index** | **int** |  | [optional] 
**name** | **str** |  | [optional] 
**oper_status** | **bool** |  | [optional] 

## Example

```python
from graphiant_sdk.models.mana_v2_circuit_interface import ManaV2CircuitInterface

# TODO update the JSON string below
json = "{}"
# create an instance of ManaV2CircuitInterface from a JSON string
mana_v2_circuit_interface_instance = ManaV2CircuitInterface.from_json(json)
# print the JSON string representation of the object
print(ManaV2CircuitInterface.to_json())

# convert the object into a dict
mana_v2_circuit_interface_dict = mana_v2_circuit_interface_instance.to_dict()
# create an instance of ManaV2CircuitInterface from a dict
mana_v2_circuit_interface_from_dict = ManaV2CircuitInterface.from_dict(mana_v2_circuit_interface_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


