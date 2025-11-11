# ManaV2NetworkSlice


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**id** | **int** |  | [optional] 
**peers** | [**List[ManaV2NetworkSlicePeer]**](ManaV2NetworkSlicePeer.md) |  | [optional] 
**slice_index** | **int** |  | [optional] 
**tags** | **List[str]** |  | [optional] 

## Example

```python
from graphiant_sdk.models.mana_v2_network_slice import ManaV2NetworkSlice

# TODO update the JSON string below
json = "{}"
# create an instance of ManaV2NetworkSlice from a JSON string
mana_v2_network_slice_instance = ManaV2NetworkSlice.from_json(json)
# print the JSON string representation of the object
print(ManaV2NetworkSlice.to_json())

# convert the object into a dict
mana_v2_network_slice_dict = mana_v2_network_slice_instance.to_dict()
# create an instance of ManaV2NetworkSlice from a dict
mana_v2_network_slice_from_dict = ManaV2NetworkSlice.from_dict(mana_v2_network_slice_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


