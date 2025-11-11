# ManaV2OspfArea


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**area_id** | **str** |  | [optional] 
**bfd** | [**ManaV2BfdInstance**](ManaV2BfdInstance.md) |  | [optional] 
**bfd_neighbors** | [**List[ManaV2BfdNeighbor]**](ManaV2BfdNeighbor.md) |  | [optional] 
**id** | **int** |  | [optional] 
**interfaces** | [**List[ManaV2OspfInterface]**](ManaV2OspfInterface.md) |  | [optional] 
**name** | **str** |  | [optional] 
**type** | **str** |  | [optional] 

## Example

```python
from graphiant_sdk.models.mana_v2_ospf_area import ManaV2OspfArea

# TODO update the JSON string below
json = "{}"
# create an instance of ManaV2OspfArea from a JSON string
mana_v2_ospf_area_instance = ManaV2OspfArea.from_json(json)
# print the JSON string representation of the object
print(ManaV2OspfArea.to_json())

# convert the object into a dict
mana_v2_ospf_area_dict = mana_v2_ospf_area_instance.to_dict()
# create an instance of ManaV2OspfArea from a dict
mana_v2_ospf_area_from_dict = ManaV2OspfArea.from_dict(mana_v2_ospf_area_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


