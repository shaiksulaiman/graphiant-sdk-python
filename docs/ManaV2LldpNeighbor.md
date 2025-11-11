# ManaV2LldpNeighbor


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**id** | **int** |  | [optional] 
**interface** | **str** |  | [optional] 
**ip_address** | **str** |  | [optional] 
**mac_address** | **str** |  | [optional] 
**port** | **str** |  | [optional] 
**system_name** | **str** |  | [optional] 
**vendor** | **str** |  | [optional] 

## Example

```python
from graphiant_sdk.models.mana_v2_lldp_neighbor import ManaV2LldpNeighbor

# TODO update the JSON string below
json = "{}"
# create an instance of ManaV2LldpNeighbor from a JSON string
mana_v2_lldp_neighbor_instance = ManaV2LldpNeighbor.from_json(json)
# print the JSON string representation of the object
print(ManaV2LldpNeighbor.to_json())

# convert the object into a dict
mana_v2_lldp_neighbor_dict = mana_v2_lldp_neighbor_instance.to_dict()
# create an instance of ManaV2LldpNeighbor from a dict
mana_v2_lldp_neighbor_from_dict = ManaV2LldpNeighbor.from_dict(mana_v2_lldp_neighbor_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


